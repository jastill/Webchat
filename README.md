# Webchat

You can use this webchat to talk with your bot created on [Recast.AI](https://recast.ai).

## Usage

To use this webchat, you first need to create a **Webchat** channel on [Recast.AI](https://recast.ai).
Go on your bot, in the **Connect** tab, and click on **Webchat**. A modal where you can modify your preferences opens.
You can set the colors of the webchat, the icons used for the bot and the user, the onboarding message and much more.

Once you're satisfied with the settings, click on the **SAVE** button. A script tag appears, and you just have to copy paste it
in your web page to embed the webchat.

```
<script
  src="https://cdn.recast.ai/webchat/webchat.js"
  channelId="YOUR_CHANNEL_ID"
  token="YOUR_CHANNEL_TOKEN"
  id="recast-webchat"
></script>
```

However, if you want to customize the webchat in more details, you can fork this project! Once you're done, build it,
host it, and modify the *src* field of the script.

## Installation

Clone the repository and install the dependencies.

```
$> git clone GITHUB_URL
$> cd webchat
$> npm install
```

#### Run in development mode

```
$> npm run start
```

#### Eslint + prettier

```
$> npm run prettier
```

#### Build for production

```
$> npm run build
```

## License

Copyright (c) [2016] Recast.AI

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NON INFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.