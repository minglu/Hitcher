# Hitcher

## Enviroment setup

- Install [Node.js](https://nodejs.org/en/).
- Install Expo CLI command line utility, react native CLI
- Go to directory and start to run
```
npm install -g expo-cli
npm install -g react-native-cli
cd Hitcher
expo start
```
if you can not install expo cli globally with permission issue please try the following:
```
mkdir ~/.npm-global
npm config set prefix '~/.npm-global'
export PATH=~/.npm-global/bin:$PATH
source ~/.profile
npm install -g jshint
```
then try npm install expo-cli --global
