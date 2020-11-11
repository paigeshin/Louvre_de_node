# Louvre_de_javascript

# Checklist 

- express session
- express session store
- bcrypt.js
- CSRF Protection by `curf`
- Global error handler (middleware)
- email third party `your choice`
- flash-message
- pagination
- Input Validation `express-validator` or `validator` 
- file manager by `multer`
- CORS error prevention => Set Header Properly
- JWT (if it's just restful api server) by `jsonwebtoken`
- Secure Header by `helmet`
- Asset Compression by `compression`
- Logging by `morgan`

- Testing Modules
    - `mocha` to execute the test code
    - `chai` to validate the test outcome
    - `sinon` to manage side effects / external dependencies


# Atlas Configuration

1. White list IP Address
2. Create User
3. Connect to Cluster
4. Use Mongo Compass

# NPM

[npm & Node as a Build Tool](https://www.notion.so/npm-Node-as-a-Build-Tool-614b1b7ea2e14130bb634caa0ee95a98)

# Preparing the code for Production (Checklist)

### Use Environment Variables
⇒ Avoid hard-coded values in your code

### Use Production API Keys
⇒ Don't use that testing Stripe API

### Reduce Error Output Details
⇒ Don't send sensitive info to your users 

### Set Secure Response Headers
⇒ Implement best practices

### Add Asset Compression
⇒ Reduce Response Size 

### Configure Logging
⇒ Stay up to date about what's happening

### Use SSL/TLS
⇒ Encrypt data in transit

ℹ️ Often, `Add Asset Compression` `Configure Logging` `Use SSL/TLS` are handled by the Hosting Provider

# Template

[Classic Node Server](https://github.com/paigeshin/my_classic_node_server_template)

[REST API Server Template, using only promises](https://github.com/paigeshin/MY_REST_API_TEMPLATE)

[REST API SERVER Template, using only async-await](https://github.com/paigeshin/REST_API_NODE_ASYNC_AWAIT)

[WEB Socket Template](https://github.com/paigeshin/websocket_node_rest_api_template)

[GraphQL Template](https://github.com/paigeshin/node_js_graphql_template)


# Modules

[Node.js jwt](https://www.notion.so/Node-js-jwt-afc932a512fc46f9a8136a6478efd93b)

[Handle CORS error](https://www.notion.so/Handle-CORS-error-ad6248da4bfc403bb5186c7fff2e9a62)

[REST API Basic](https://www.notion.so/REST-API-Basic-88b4fa06243e45f58345fe3bbeb243ac)

[Payment Process](https://www.notion.so/Node-js-Error-Handling-2e5aee4ae2bf442d9eaf3e69a5e99bfa)

[Erorr handling](https://www.notion.so/Node-js-Error-Handling-2e5aee4ae2bf442d9eaf3e69a5e99bfa)

[ajax, fetch without query](https://www.notion.so/Ajax-fetch-without-jquery-7f77e109ab8c4f70a86f6a30ad2b18f8)

[Express Validator](https://www.notion.so/Express-validator-83500d3ae944417abcdc7ba269d2716b)

[node.js bcrypt.js](https://www.notion.so/node-js-bcrypt-js-8ccf586943c34062bf9a3b6472d203c1)

[node.js CSRF protection](https://www.notion.so/node-js-CSRF-protection-5cd1e81b98ba4150a98e0c0155c8acc2)

[Node.js flash message](https://www.notion.so/node-js-flash-message-8ea3588188df4806a92436eb3b0c087d)

[Node.js sending email using sending grid](https://www.notion.so/Node-js-sending-email-using-sending-grid-26067d3a85fc49b0a3c18dc480be74ff)

[Swift - node Multipart-Form handling](https://www.notion.so/Swift-node-Multipart-Form-handling-ba7fa62992bd421a93bdc5b8ec04d00f)

[https://github.com/paigeshin/Swift-Node-MultiPart-Form-Example](https://github.com/paigeshin/Swift-Node-MultiPart-Form-Example)

# Backend

[ajax, fetch without query](https://www.notion.so/Ajax-fetch-without-jquery-7f77e109ab8c4f70a86f6a30ad2b18f8)

[Pagination](https://www.notion.so/Node-pagination-10cbd2cf2cf9401eb2e2353208266cc2)

[File upload & Downloads node.js](https://www.notion.so/File-upload-Downloads-node-js-921844434ef549bc9bfc77b3f744a3b2)

[node pdf](https://www.notion.so/node-pdf-3b5108d0767f4f139babdaef00c2949f)

[Node.js sending email using sending grid](https://www.notion.so/Node-js-sending-email-using-sending-grid-26067d3a85fc49b0a3c18dc480be74ff)

[node.js Reset password ](https://www.notion.so/node-js-Reset-password-a901e3dfda6445f7a0ed7c87123a0e24)

[Node.js restrict permission (Authorization)](https://www.notion.so/Node-js-restrict-permission-Authorization-84cba96f1dd34a718b4470547ca0b528)

[node.js Advanced Authentication](https://www.notion.so/node-js-Advanced-Authentication-7eba8b9c68954c35a41ec9ee3e6f5482)

[Node.js User Authentication](https://www.notion.so/Node-js-User-Authentication-0d315d35783b4b988e714cbb624cab96)

[Node.js middleware example](https://www.notion.so/Node-js-middleware-example-372e455b87074ef488431406bf168d43)

[Express Session document on git](https://github.com/expressjs/session )

[Express session document on NPM](https://www.notion.so/20-06-14-2173eb962e024b41b91a1efe8e06e0ba)

[Node.js Dynamic Routes ](https://www.notion.so/Node-js-Dynamic-Routes-8baa1ea9de2c4bff9ea409fc12cff1d2)

[Node, module exports](https://www.notion.so/Node-the-way-of-module-exports-1077df2e27e3424c8e0e43b875ae06ff)

[node.js express MVC pattern](https://www.notion.so/node-express-MVC-Pattern-d53eb63b06c847f29a1c2bbfb3f10c7d)

[passport - node.js authetication setup - version of Colt Steele](https://www.notion.so/passport-node-js-authetication-setup-version-of-Colt-Steele-6d3fb9a884ae48d4bba053d89275a006)

[RESTFUL routes node.js](https://www.notion.so/RESTFUL-routes-node-js-3d2681c5459241d3b2bea08ec91541b2)

[Nodemon - automate restart node_server](https://www.notion.so/Nodemon-automate-restart-node_server-208c7eb6d1ed48c09da2aa987a8d4c02)

[Mern Stack, react, node 동시에 실행하기](https://www.notion.so/Mern-Stack-react-node-298ab1fd114a488db658e19248e0a013)

[Retrofit2 - node.js - arraylist 보내기 ](https://www.notion.so/Retrofit2-node-js-arraylist-b642cfb4369d44148bae7beec4bf9f91)

[node.js Bulk sql](https://www.notion.so/node-js-Bulk-sql-ed9837588fc84ab3ab8b3ee5c5b3b145)

[header, authentication node.js base64 decode](https://www.notion.so/header-authentication-node-js-base64-decode-2348ab738a9e46c197d6938bbc7de3d3)

[node webscraping ](https://www.notion.so/node-webscraping-e3d50bd94e844f20aebd0d1d1c895403)

[Javasript Basic System](https://www.notion.so/node-js-basic-max-83cba4070d184385a3d3ae9064e1573b)

[node.js low level server example](https://www.notion.so/Node-js-low-level-Basic-Server-b1355e437dc44220b5d690d28c3d3c9b)

[express in detail](https://www.notion.so/express-in-detail-9a26c4e485074e38bf4f20e40e7f5084)

[Working with express in detail, path, middleware, routes, send files](https://www.notion.so/Working-with-express-in-detail-path-middleware-routes-send-files-4fc6357e5aa64650ba205424ace4eb0f)

# Mongo

[Mongoose document on git](https://github.com/Automattic/mongoose)

[Mongoose official document](https://mongoosejs.com/docs/guide.html)

[Mongoose Basic](https://www.notion.so/Mongoose-Basic-57f5dc7086ba43b09bf1ebca42341d0b)

[node.js mongo basic CRUD Model](https://www.notion.so/node-js-mongo-basic-CRUD-Model-4739afde1f9b48a6b7e6ca439b1f9762)

[node.js mongo basic code implementation](https://www.notion.so/node-js-mongo-basic-code-implementation-575fc9a096c24b3e90d87e98222e2e84)

[Mongo + Node Basic ](https://www.notion.so/Mongo-Node-Basic-1bf5c3753b1441b3a9ce4b770bad84e6)

[Atlas & Mongo Installation ](https://www.notion.so/Atlas-Mongo-Installation-c3dc01a0b736479ea1813dded6d233cb)

# MYSQL 

[Node.js using mysql2, raw version](https://www.notion.so/Node-js-using-mysql2-raw-version-ac1179f229d34358bd1a4e05be8a9092)

[Sequelize](https://github.com/paigeshin/node.js-orm-sequelize-sql-mysql)

# General
[sql vs nosql](https://www.notion.so/sql-vs-Nosql-a56c1b97a9984f0f89ba1e99cb23e966)

# Template Engine

[Pug 사용법](https://www.notion.so/node-js-pug-tutorial-d7d25ee490dd4cafb51815d9a8444eac)

[Handle bar 사용법](https://www.notion.so/template-engine-handlebar-895a5c3fc3bc4acbb5802b2173475c48)

[ejs 사용법](https://www.notion.so/ejs-e81eeb74dd2741a0ab0929869c47494d)

# Tools

[node, write CSV](https://www.notion.so/node-write-CSV-b550994971314ad8b90437f3b9596d86)

[node.js JSON Ordering](https://www.notion.so/node-js-JSON-Ordering-b10051718db14f44a9ea0973aad30adb)

[node, 두 개의 json file을 읽고 새로 파일을 쓰기](https://www.notion.so/node-json-file-46084f5f6f3f41d18aa5f6f0df13fa4f)

[Write json file, node.js ](https://www.notion.so/Write-json-file-node-js-eb607af10f274360bdedf370ef1f7292)

[Read CSV, node](https://www.notion.so/Read-CSV-node-123496239fa142c7bb76a157838cb8ce)

# Common

[Package.json, script, explained, recap](https://www.notion.so/Package-json-script-explained-recap-361a6aec6dc64764bc976c26628b80db)

[Javascript Basic Syntax](https://www.notion.so/Javascript-Basics-ES6-cead68ceb5e64df8ba1b562384069eee)

[Javascript debugging & Error Types](https://www.notion.so/Javascript-Node-js-Tools-28b650d5e6f84141ab697e5b6f691e31)

# Debugging

[504 Error app engine, node](https://www.notion.so/504-Error-app-engine-node-d9a26796b6744752a19eecebfd05eb61)


# Lectures

[Node Complete Guide](https://www.notion.so/NodeJS-The-Complete-Guide-d347014dbbc847199d4ec4a60a700856)

# Grammar

[javascript - Call async/await functions in parallel - Stack Overflow](https://stackoverflow.com/questions/35612428/call-async-await-functions-in-parallel)

[javascript about await](https://www.notion.so/javascript-about-await-2ee12ec510394da680396189ed1a4a31)

[Async Await](https://www.notion.so/Javascript-node-js-Async-Await-ab3251a3c19644d3966cd8559fcdd15f)

[Javascript replace all regular expression](https://www.notion.so/Javascript-replace-all-regular-expression-132212ad28dd43a6af47338f9b42e882)

# Template

[Node.js REST API Template](https://www.notion.so/Node-js-REST-API-Template-f032f654b00d4eceb188c5e95a77619a)


# websocket_node_rest_api_template
[Web Socket - notion](https://www.notion.so/node-websocket-rest-api-template-935a1c69f0264f3bafa55123e82ece63)

[Web Socket - github](https://github.com/paigeshin/websocket_node_rest_api_template)

# File

[Delete local file, node.js](https://www.notion.so/delete-local-file-node-js-34eabd48e95f4f878ea228d2a06ea1f9)

# vsCode for Javascript

[vsCode Tutorial](https://www.notion.so/vsCode-Tutorial-75e4030de93f4bd0a8a2b1826bee4ea3)

[vsCode Extension Recommendation](https://www.notion.so/vsCode-Extension-Recommendation-1738a5b211134cf785745d3ed745553d)

[vsCode Debugging](https://www.notion.so/vsCode-Debugging-357435e407ee4d1695eb2d8b31caf5c7)

# Storing User Generated Files on Storage Server 
=> Mostly, cloud server doesn't keep user-generated files.

[amazon s3](https://aws.amazon.com/s3/)

[multer s3](https://www.npmjs.com/package/multer-s3)

[s3 proxy](https://www.npmjs.com/package/s3-proxy)

[aws sdk for node](https://aws.amazon.com/sdk-for-node-js/)

# Deployment

[Storing User-generated Files on Cloud, additional packages](https://www.notion.so/Storing-User-generated-Files-on-Cloud-additional-packages-7517543319fd4ce989947595b5cbf502)

[Deployment](https://www.notion.so/Deployment-08c72ea4b15c4cce81e78bfe2c605122)

[Setting Secure Response Headers with Helmet](https://www.notion.so/Setting-Secure-Response-Headers-with-Helmet-bafd3ef5d5144032926a97b420dcfb82)

[Configuring Env Variables with nodemon](https://www.notion.so/Configuring-Env-Variables-with-nodemon-18b194e9c3074c488c148cf3ad2b9bca)

[Optimize asset with compression](https://www.notion.so/Optimize-asset-with-compression-70b658b5565447a682292f411c830d9d)

[Set up Request Logging with Morgan](https://www.notion.so/Set-up-Request-Logging-with-Morgan-a4cb2565799f4746a9dfb9d01bd0ecc1)

[SSL/TLS manual installation](https://www.notion.so/SSL-TLS-manual-installation-d65fff489a3e47b9b9901153f1b64132)

[How Hosting Provider works internally?](https://www.notion.so/How-Hosting-Provider-works-internally-fa45e31ae27d4153a28a686937eab464)

[Heroku Tutorial](https://www.notion.so/Heroku-Tutorial-e72eae26f2434cada9351a2e9d6b51b0)

# Next Gen

[Modern JavaScript & Node.js, ESModule and CorePromise](https://www.notion.so/Modern-JavaScript-Node-js-ESModule-and-CorePromise-86e73e700c6b4335aeb70a396f65c02b)

# Unit Test

[Testing - Automated code Testing](https://www.notion.so/Testing-Automated-code-Testing-20fd00cf9a0c4edc98f7216b3b30c326)

[Unit Test on github](https://github.com/paigeshin/node_js_unit_test_example)

# TypeScript

[Typescript basic on git](https://github.com/paigeshin/typescript_tutorial)

[Typescript basic on notion](https://www.notion.so/Typescript-Tutorial-4c0adb4aadab4c01875017a0a250e598)

[Node & TypeScript Basic Rest API Example on git](https://github.com/paigeshin/node-typescript-basic-REST-API-example)

[Node & TypeScript Basic Rest API Example on notion](https://www.notion.so/Node-TypeScript-Basic-Rest-API-Example-45d4e4940a484c0186bd91a4fc9599f5))


# Management

[node.js update to lastest stable version on MacOS](https://www.notion.so/node-js-update-to-lastest-stable-version-5ec3e53582934c80a361044b78f6fdbd)

# Study Direction

[Node.js Next Subject ](https://www.notion.so/Node-js-Next-Subject-66e6ca1769af433f981b80e124d50294)

# Node Default Module 

- path
- fs
- url
- crypto

# Push Mesasge - APN 

[node - swift, git repository](https://github.com/paigeshin/swift-apn-node-pushmessage-using-npm-package)

[node - apn](https://www.notion.so/node-apn-c40e0cd139d443f7a995dfa22ef09369)

[https://solarianprogrammer.com/2017/02/14/ios-remote-push-notifications-nodejs-backend/](https://solarianprogrammer.com/2017/02/14/ios-remote-push-notifications-nodejs-backend/)

[https://www.npmjs.com/package/apn](https://www.npmjs.com/package/apn)

[https://levelup.gitconnected.com/send-push-notification-through-apns-using-node-js-7427a01662a2](https://levelup.gitconnected.com/send-push-notification-through-apns-using-node-js-7427a01662a2)

[https://developer.apple.com/library/archive/documentation/NetworkingInternet/Conceptual/RemoteNotificationsPG/APNSOverview.html](https://developer.apple.com/library/archive/documentation/NetworkingInternet/Conceptual/RemoteNotificationsPG/APNSOverview.html)

[https://developer.apple.com/library/archive/documentation/NetworkingInternet/Conceptual/RemoteNotificationsPG/CreatingtheNotificationPayload.html](https://developer.apple.com/library/archive/documentation/NetworkingInternet/Conceptual/RemoteNotificationsPG/CreatingtheNotificationPayload.html)

# Push Server Complete with FCM

[Firebase-admin for FCM](https://www.notion.so/node-firebase-admin-for-fcm-3ea5722c571e42a787ede9278d7b5935)

[Complete Source code](https://github.com/paigeshin/fcm_push_server_ios_complete_version)

# Push Server Complete without FCM

[Push Server for Swift without FCM, using only npm package](https://github.com/paigeshin/swift-apn-node-pushmessage-using-npm-package)



# Maximillian, Node.js Bootcamp index

[node.js Basic](https://www.notion.so/node-js-Basic-ded70597132f4a23a86e94b70b953937)

[Javascript Basics ](https://www.notion.so/Javascript-Basics-4614bff5daf54c709d97fdbe9db75ee6)

[Understanding the basics ](https://www.notion.so/Understanding-the-basics-7bddd6c45eee456f961005728246c921)

[Node.js tools ](https://www.notion.so/Node-js-tools-6cd788e4bf4b49949b2a1d40967f79d2)

[Working with Express.js](https://www.notion.so/Working-with-Express-js-a63a76ef5ec04a638cbae83ff28f3797)

[Working with Dynamic Content & Adding Templating Engines](https://www.notion.so/Working-with-Dynamic-Content-Adding-Templating-Engines-9761c8c1d7e84c0f81dcf401957207b6)

[Pug Tutorial](https://www.notion.so/Pug-Tutorial-fe21bb89f7f54a04926d14f2b7467316)

[ejs 사용법](https://www.notion.so/ejs-b7a2f6e4c8484d7daccdfa83809309ae)

[Model - View - Controller, node express ](https://www.notion.so/Model-View-Controller-node-express-32fe7e5602694e1c961cea537a0e8080)

[Dynamic Routes & Advanced Models ](https://www.notion.so/Dynamic-Routes-Advanced-Models-a416ceeecec746f1af233be8a27aeac7)

[SQL vs NoSQL ](https://www.notion.so/SQL-vs-NoSQL-9ea24ced78eb48619d87d4c68242a4c0)

[Mysql- node, raw version ](https://www.notion.so/Mysql-node-raw-version-88f777e3e58d46c2b23c7ede4ca9a762)

[Squelize](https://www.notion.so/Squelize-c0be68039e35403c918ca9d9397a4101)

[Mongo DB](https://www.notion.so/Mongo-DB-86170d8b7c4841379f5b53e948a1410d)

[Mongoose ](https://www.notion.so/Mongoose-68713af010f84a338e36557a11ce2e4e)

[Session & Cookies ](https://www.notion.so/Session-Cookies-179d861307c040c698b177be3554d3e3)

[User Authentication, Restricting Access](https://www.notion.so/User-Authentication-Restricting-Access-ac3dedb2e83045388fcda45ec6a746d5)

[Sending Email ](https://www.notion.so/Sending-Email-d713afc10c07476399bb16008fb09d1b)

[Advanced Authentication](https://www.notion.so/Advanced-Authentication-05ecc3a6d85d45c3829f62715a664b93)

[Understanding Validation](https://www.notion.so/Understanding-Validation-6debd0fdf1634fdaad7862679ac9a2a6)

[Error Handling](https://www.notion.so/Error-Handling-d9f0f62c92164fef822735b1f434ae2a)

[File Uploads & Downloads](https://www.notion.so/File-Uploads-Downloads-eba48892c0524eeeb550b7aecddbea4e)

[Pagination](https://www.notion.so/Pagination-d478c3eb240b454cabbb53854847ff7c)

[Asynchronous Javascript Requests](https://www.notion.so/Asynchronous-Javascript-Requests-bca329bc3abf4e758d8a43a1ebf94370)

[Node Payment Process, Stripe Implementation ](https://www.notion.so/Node-Payment-Process-Stripe-Implementation-48639e5de3c048fba58c73d1d5d99382)

[REST APIs](https://www.notion.so/REST-APIs-09a8f34c72b44e35a9d50459c2dec735)

[Advanced REST API Topics](https://www.notion.so/Advanced-REST-API-Topics-6e99ed53628040e3ad12148bc274b606)

[Async/Await](https://www.notion.so/Async-Await-2f879735449e4c7b902a7e81aace5ace)

[Real-Time Web Services, Websocket](https://www.notion.so/Real-Time-Web-Services-Websocket-e3fc90fc5c884977b8ecf0d571210693)

[GraphQL](https://www.notion.so/GraphQL-8e40bd4c685341b4b4f204ca19cc583c)

[Deployment](https://www.notion.so/Deployment-08c72ea4b15c4cce81e78bfe2c605122)

[npm & Node as a Build Tool](https://www.notion.so/npm-Node-as-a-Build-Tool-614b1b7ea2e14130bb634caa0ee95a98)

[Modern JavaScript & Node.js, ESModule and CorePromise](https://www.notion.so/Modern-JavaScript-Node-js-ESModule-and-CorePromise-86e73e700c6b4335aeb70a396f65c02b)

[Testing - Automated code Testing](https://www.notion.so/Testing-Automated-code-Testing-20fd00cf9a0c4edc98f7216b3b30c326)

[Typescript Tutorial](https://www.notion.so/Typescript-Tutorial-4c0adb4aadab4c01875017a0a250e598)

[TypeScript SetUp](https://www.notion.so/TypeScript-SetUp-adbdc62b78da45d9a29a2631f0cc1c04)

[Node & TypeScript Basic Rest API Example](https://www.notion.so/Node-TypeScript-Basic-Rest-API-Example-45d4e4940a484c0186bd91a4fc9599f5)

[Next Steps](https://www.notion.so/Next-Steps-c1112db052e24321b791116bd1b76006)

# Mongo

[Louvre_de_mongo](https://github.com/paigeshin/Louvre_de_mongo)


# Articles

[ID token vs Access token](https://medium.com/@nilasini/id-token-vs-access-token-17e7dd622084)

[About json schema](https://json-schema.org/understanding-json-schema/structuring.html)

[Amazon API Gateway mapping template](https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-mapping-template-reference.html)

[Amazon Cognito Integration for web, iOS and android](https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-integrate-apps.html)

[Android & iOS Cognito Impelementation](https://aws.amazon.com/blogs/aws/new-aws-amplify-libraries-for-android-and-ios/)

# Amazon Lambda

[Lambda code example on github](https://github.com/paigeshin/amazon_lambda_node_example)

[Running Node/Express Apps via Amazon Lambda + API Gateway](https://github.com/awslabs/aws-serverless-express)

[MPA node-express application practical example](https://github.com/paigeshin/MPA_Node_Express_Serverless_Example)