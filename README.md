# surfmarkers_app
## Getting started on a Chromebook

### 1. Setup the firebase app 
- https://pub.dev/packages/firebase_auth#-readme-tab-
1. Enable Google authentication:
- Go to Firebase Console for your new instance.
- Click "Authenticate" in the left-hand menu
- Click the "sign-in method" tab
- Click "Google" and enable it

2. Create Cloud Functions (to make Feed work)
- You're going to need Nodejs on your Chromebook [Installing Nodejs on your Chromebook](https://medium.com/@jacoboakley/web-development-with-a-chromebook-installing-nodejs-4e358b82a31b)
- You're also going to need to [install the Google Cloud SDK](https://cloud.google.com/sdk/docs/downloads-interactive)
- Once the Google Cloud SDK is installed, you'll need to [authenticate your request with your Google account]( https://stackoverflow.com/questions/42043611/could-not-load-the-default-credentials-node-js-google-compute-engine-tutorial)
- If you're not using a browser or an emulator and testing with your phone, you should use [firebase login --no-localhost](https://stackoverflow.com/questions/43828039/how-to-login-to-firebase-tools-on-headless-remote-server) to login to 'fire-base' tools on a headless remote server.

