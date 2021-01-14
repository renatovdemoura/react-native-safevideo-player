# react-native-safevideo-player

SafeVideo player for react native apps

## Installation

```sh
yarn add react-native-video
yarn add react-native-safevideo-player
```

## Usage

```js
import SafevideoPlayer from "react-native-safevideo-player";

// ...

<SafeVideoPlayer
  onError={handleError}
  style={StyleSheet.absoluteFill}
  source={{ uri: 'https://bitdash-a.akamaihd.net/content/MI201109210084_1/m3u8s/f08e80da-bf1d-4e3d-8899-f0f6155f6efa.m3u8' }}
/>
```

## Examples

```sh
# Android app
yarn example android
# iOS app
yarn example ios
```

<img src="https://cdn.discordapp.com/attachments/770721962464247830/799283972973658112/ezgif.com-video-to-gif-3.gif" width="200" />

## License

MIT
