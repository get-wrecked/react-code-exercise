# Medal TV React Code Exercise

Thank you for applying to Medal! Congratulations on getting this far into the application process. This exercise is designed to expose our development team to your code style and UI/UX intuitions.

## Specification

We would like to see your version of a video feed. Medal has a video feed, but don't let that dictate your design. We want to see how you would do it using the tools we use everyday. Included in this project is our video player, please use the one provided as it is different than the one we use on production. You can get a live feed of clips on the platform using the [API developer documentation](https://docs.medal.tv/api). The videos.json file is also included for your convenience (but please use the API in your final solution).

### Requirements
- List all video objects using our video player
- A user should be able to play the individual videos within the feed

### Technology Requirements
- Use ReactJS
- Use our provided video player, reference the readme file within the zip file for additional information (hint: videoOpts is a required prop). You will not be able to install from Github like described in the video player readme (it is a private repo), you must use the one included in the zip file.
- The app server must be able to be ran using this command:
  `npm install && npm run start`

### Submitting Work

**DO NOT UPLOAD YOUR SOLUTION TO A PUBLIC GITHUB REPO**

Feel free to clone this repo or download the two resources (the Medal Video player zip file and videos.json). When you have completed your work, email ken@medal.tv a zip file of the project (or a link to a zip file if your email client doesn't allow you to send zip files, please do not include your `node_modules` folder).

#### Can I use tools like NextJS or Create React App?
Yes absolutely, use any tool you would like as long as it allows you to follow the technology requirements.

#### How do I include the video player package?
Please use the `file:` syntax in your package.json file. You can learn more here: https://docs.npmjs.com/files/package.json#local-paths
