= Youtube Downloader

This is an application written in Go that allows you to download videos from YouTube.
The intention of this application is not to be used for illegal puporses but as a way of learning the breadth of the
GO langauge.

## How it works

- Parse the video ID you input in URL
  - ex: `https://www.youtube.com/watch?v=rFejpH_tAHM`, the video id is `rFejpH_tAHM`
- Get video information via video id.
  - Use URL: `http://youtube.com/get_video_info?video_id=`
- Parse and decode video information.
  - Download URL in "url="
  - title in "title="
- Download video from URL
  - Need the string combination of "url"
