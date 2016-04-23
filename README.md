# MoonMail (BETA)

[![serverless](http://public.serverless.com/badges/v3.svg)](http://www.serverless.com)
[![Twitter](https://img.shields.io/twitter/url/https/github.com/microapps/MoonMail.svg?style=social)](https://twitter.com/intent/tweet?text=Wow:&url=%5Bobject%20Object%5D)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/microapps/MoonMail/master/LICENSE)


Send email marketing campaigns with [Amazon SES](https://aws.amazon.com/ses/). Let [Amazon Lambda](https://aws.amazon.com/lambda/) compose email by email and literaly scale it to infinite. 

With MoonMail you can: create lists of recipients, store recipients (email addresses) within a [DynamoDB](https://aws.amazon.com/dynamodb/), send email marketing campaigns and track opens and clicks.

**The biggest magic of MoonMail: SEND BILLIONS OF EMAILS WITH NO SERVERS!**

[See the wiki for detailed specs and infrastructure graphs.] (https://github.com/microapps/MoonMail/wiki)


## Live Features

* Create and store recipient lists
* Compile and send email campaigns

## Upcoming Features

* Parse (track) clicked links within an email
* Download the full package as a node module
* One click upload to S3 of a recipient list + html email and shoot it using your Terminal


## Getting Started

You need to have installed the [Serverless Framework](https://github.com/serverless/serverless) (version 0.5.2 or higher is required to run the MoonMail API).

Initialize the Serverless project:
    
    sls project init
    
Create all the needed resources in your AWS account:

    sls resources deploy

Deploy all the Lambda functions:

    sls function deploy
    
Deploy MoonMail events:

    sls event deploy

Create the API Gateway endpoints:

    sls endpoint deploy

## License

MoonMail is available under the MIT license. See the LICENSE file for more info.