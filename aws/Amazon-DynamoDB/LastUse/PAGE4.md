#### Ingredients
## 4. Connect your skill to Lambda <a id="title"></a>
<hr />

Here is how to copy and paste your Lambda function ARN to the Skill endpoint.

1. Within the AWS Lambda function page, the ARN, or Amazon Resource Name, is shown near the top right, such as
 *  ``` arn:aws:lambda:us-east-1:333304287777:function:HelloWorld ```
1. Copy this ARN
 + ![Amazon Resource Name](https://m.media-amazon.com/images/G/01/cookbook/arn._TTH_.png)
1. Go to the browser tab at [developer.amazon.com](https://developer.amazon.com) and navigate into your skill's Configuration page.
1. Click the radio button for Service Endpoint Type: AWS Lambda ARN
1. Pick a geographical region that is closest to your target customers
1. Click into the textbox that appears, and Paste.
1. Scroll down and click Save.
1. You should see a green checkbox next to the Configuration menu item.
1. If you get an error, confirm you have previously added an ASK Trigger to your Lambda function.


#### Test your skill

1. Open your skill and say 'help'.
1. Verify the response indicates the time since you last used the skill.
1. Say 'stop'
1. Wait a few minutes
1. Repeat

You should hear a help message that informs you the time since your last visit.


<hr />
Back to the [Home Page](../../../README.md#title)
