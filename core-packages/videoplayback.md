# TVideoPlayback
Help page for the VideoPlayback component on InstaJS Cloud IDE. videotest.frm is provided in this repository to demonstrate the methods and properties of this component.

## Methods:

`createVideoPlayer(value: TVideoType, videoId: string, autoplay: boolean)`

This method initializes and creates the video player element. The first parameter specifies the type of video which is either `Core.VideoPlayback.TVideoType.youtube` or `Core.VideoPlayback.TVideoType.mp4Video`. The videoId parameter takes in the video id for youtube (eg. `dVkK36KOcqs` in https://www.youtube.com/watch?v=dVkK36KOcqs) and the url for the mp4 videos. autoPlay should be set to true if the video is supposed to play as soon as the page loads.

## Properties:

`fullScreen: boolean`

this property specifies if the video player should be allowed to go fullscreen

`videoVolume: number`

This property specifies video volume. For Youtube videos this is from 0 to 100. For Vimeo and HTML5 videos, this should be set between 0 and 1 for example: 0.5 for half the volume.

`htmlVideoThumbnail: string`

this property allows for a thumbnail to be set for HTML5 videos. The value is the url of the thumbnail image.
