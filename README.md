# Dino Jump Jump

The T-Rex runner game with voice control.

![game cast](assets/screenshot.gif)

## How To Install and Run the Project

##### ❗Important❗

- Before running this app, you need to upgrade your AssemblyAI account. The real-time API is only available to upgraded accounts at this time.
- Running the app before upgrading will cause an **error with a 402 status code.** ⚠️
- To upgrade your account you need to add a card. You can do that in your dashboard [here](https://app.assemblyai.com/)!

##### Instructions

1. Clone the repo to your local machine.
2. Open a terminal in the main directory housing the project. In this case `dino-jump-jump-main`.
3. Run `npm install` to ensure all dependencies are installed.
4. Add your AssemblyAI key to line 13 of [`server.js`](https://github.com/AssemblyAI/realtime-transcription-browser-js-example/blob/62e07e1d2a7ee2e13349c4e817b048e41334c4ec/js/server.js#L13)
5. Start the server with the command `npm run server` (will run on port 8000).
7. Open a second terminal in the main directory of the project and start the client side with `npm run client` (will run on port 3000).
8. Have fun
