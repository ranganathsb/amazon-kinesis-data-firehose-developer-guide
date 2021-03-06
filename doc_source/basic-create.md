# Creating an Amazon Kinesis Firehose Delivery Stream<a name="basic-create"></a>

You can use the AWS Management Console or an AWS SDK to create a Kinesis Firehose delivery stream to your chosen destination\. 

You can update the configuration of your Kinesis Firehose delivery stream at any time after it’s created, using the Kinesis Firehose console or [UpdateDestination](http://docs.aws.amazon.com/firehose/latest/APIReference/API_UpdateDestination.html)\. Your Kinesis Firehose delivery stream remains in the `ACTIVE` state while your configuration is updated, and you can continue to send data\. The updated configuration normally takes effect within a few minutes\. The version number of a Kinesis Firehose delivery stream is increased by a value of `1` after you update the configuration, and it is reflected in the delivered Amazon S3 object name\. For more information, see [Amazon S3 Object Name Format](basic-deliver.md#s3-object-name)\.

The following topics describe how to create a Kinesis Firehose delivery stream:


+ [Name and source](create-name.md)
+ [Transform records](create-transform.md)
+ [Choose destination](create-destination.md)
+ [Configure settings](create-configure.md)