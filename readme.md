
npm install @react-navigation/native

expo install react-native-screens react-native-safe-area-context

npm install @react-navigation/native-stack

npm install @react-navigation/drawer

expo install react-native-gesture-handler react-native-reanimated


Add in file babel.config.js

module.exports = {
  presets: ['module:metro-react-native-babel-preset'],
  plugins: ['react-native-reanimated/plugin'],
};

