# Lambda Code Files for QuickSight Developer Sandbox website (SpaceNeedleDeveloperSandbox)

## Instructions
1. cd inside the lambda/ directory.
2. run `npm install`
3. Package the index.js, package.json, and node_modules into a zip. 
   To do this, run `zip -r getDashboardEmbedURL.zip *`

You can skip above four steps by direclty using a zip file - getDashboardEmbedURL.zip stored in lambda folder as it would makes your life easier and overcomes the node modules errors which you may face if above 4 steps are followed.

4. Sign into the AWS Console and go to Lambda. Click on the GetDashboardEmbedURL function.
5. Scroll down to the 'Function code' section and click the Upload button.
6. Select the zip folder you just created, then click Save.

For more information, see step 3 at https://github.com/aws-samples/amazon-quicksight-embedding-sample
