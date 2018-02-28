# Animated Floating Reactions
Animated Floating Reactions like Facebook based on [node-emoji](https://github.com/omnidan/node-emoji).

### Installation

```sh
$ npm install --save react-native-animated-emoji
```
or

```sh
yarn add react-native-animated-emoji
```

### Usage

```javascript
import { AnimatedEmoji } from 'react-native-animated-emoji';

export const App = () => (
  <AnimatedEmoji
    index={'emoji.key'} // index to identity emoji component
    style={{ bottom: 200 }} // start bottom position
    name={'sweat_smile'} // emoji name
    size={30} // font size
    duration={4000} // ms
    onAnimationCompleted={this.onAnimationCompleted} // completion handler
  />
)
```
