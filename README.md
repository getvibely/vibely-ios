## Vibely - Music Visualizer

The ultimate Music Visualizer made for iOS! Create stunning visuals for your music using audio spectrum, waveform, starfield and other visualizers.

Transform your music into stunning visual art with Vibely, the top music visualizer and video editor for musicians, DJs, podcasters, and music enthusiasts. Vibely offers exceptional audio visualization and an easy-to-use interface that sets it apart from other apps.

[<img width="200" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Download_on_the_App_Store_RGB_blk.svg/1024px-Download_on_the_App_Store_RGB_blk.svg.png">](https://apps.apple.com/app/id1528056717)

## Known issues

### Video aspect ratio is 9:16

Some users have reported that changing the aspect ratio doesn't work while exporting. I'm working on the fix right now.

### Video freezes

Sometimes video playback gets stuck. This is known issue introduced by iOS 26 and many developers reported this weird behaviour of AVPlayerLooper. Hopefully, Apple developers will fix this issue soon. As a workaround try adjusting the player progress bar, reloading the music or setting other background options to fix it. After doing this the player loads the correct state and you can keep creating audio visualizations.

### Slow export

Currently exporting takes very long especially for longer audio files and high export settings like 60fsp/4k resolution. The rendering process is complex by its nature especially if there are lots of visual effects and visualizers playing simultaneously. However I'm working on optimizing the render pipeline and making it faster in future updates. Please be aware with me, I'm trying my best.

### Export breaks on 100%

Some of you reported to me that export fails towards the end (100%) and the video is lost. The common reason is because your device storage is full. Try removing some media files from Photos app and cleaning the trash making more space for Vibely videos.

## Work in progress

- [ ] Realtime music visualization for streaming apps

## Feature Requests

- [ ] Add layer perspective options to achieve 3D-like display
- [ ] Export optimization
- [ ] Android version of Vibely - Music Visualizer

## Changelog

Check out [Changelog](./CHANGELOG.md)

## Contact

Don't hesitate to reach out to me via support [at] getvibely [dot] app with any question or feedback. I'm always happy to improve Vibely - Music Visualizer app for you!
