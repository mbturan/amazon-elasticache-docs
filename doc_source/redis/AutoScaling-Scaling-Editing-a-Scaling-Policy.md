# Editing a scaling policy<a name="AutoScaling-Scaling-Editing-a-Scaling-Policy"></a>

You can edit a scaling policy using the AWS Management Console, the AWS CLI, or the Application Auto Scaling API\. 

## Editing a scaling policy using the AWS Management Console<a name="AutoScaling-Scaling-Editing-a-Scaling-Policy-CON"></a>

**To edit an Auto Scaling policy for an ElastiCache for Redis cluster**

1. Sign in to the AWS Management Console and open the Amazon ElastiCache console at [https://console\.aws\.amazon\.com/elasticache/](https://console.aws.amazon.com/elasticache/)\.

1. In the navigation pane, choose **Redis**\. 

1. Choose the cluster whose Auto Scaling policy you want to edit\. 

1. Choose **Actions** and then choose **Manage Auto Scaling policies**\. 

1. Choose the **Auto Scaling policies** tab\. 

1. In the **Auto Scaling policies** section, choose the Auto Scaling policy, and then choose **Edit** from the **Actions** menu\. 

1. Make the requisite changes to the policy\.

1. Choose **Update policy**\.

## Editing a scaling policy using the AWS CLI and API<a name="AutoScaling-Scaling-Editing-a-Scaling-Policy-CLI"></a>

You can use the AWS CLI or the Application Auto Scaling API to edit a scaling policy in the same way that you apply a scaling policy: 
+ When using the AWS CLI, specify the name of the policy you want to edit in the `--policy-name` parameter\. Specify new values for the parameters you want to change\. 
+ When using the Application Auto Scaling API, specify the name of the policy you want to edit in the `PolicyName` parameter\. Specify new values for the parameters you want to change\. 

For more information, see [Applying a scaling policy](AutoScaling-Scaling-Defining-Policy-API.md#AutoScaling-Scaling-Applying-a-Scaling-Policy)\.