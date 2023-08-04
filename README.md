# Deepgram iOS Filler Words

This app can help you cut out usage of filler words like "um" or "uh" that can undermine your speech and make you sound less confident. 

When you open the app, Deepgram will begin transcribing your voice. If you say the filler words "um" or "uh", the screen will flash red and play a noise to let you know.

## Demo

https://github.com/shirgoldbird/deepgram-ios-filler-words/assets/3937986/6f1ffaf3-b366-47d7-92bc-5c22411387b3

## Usage

```
git clone git@github.com:deepgram-devs/deepgram-live-transcripts-ios.git
cd deepgram-live-transcripts-ios
```
Open project in Xcode, add your key in the top of `ViewController.swift` and hit run. 

__This project exposes an API key on the client-side!__ You can set API keys to expire after a period of time, or manually revoke them via the API. 
