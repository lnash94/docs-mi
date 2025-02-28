# Amazon SQS Connector Overview

Amazon Simple Queue Service (SQS) is a fully managed message queuing service that allows you to run business applications and services so that the messaging is not dependent on the IT infrastructure itself. This means the messages can run and fail independently of each other in a way that does not cause slowdowns, system-wide faults, or a disturbance within the application. By using Amazon SQS, you can move data between distributed components of your applications that perform different tasks without losing messages or requiring each component to be always available.

Go to the <a target="_blank" href="https://store.wso2.com/connector/esb-connector-amazonsqs">WSO2 Connector Store</a> to download the AAA connector.

<img src="{{base_path}}/assets/img/integrate/connectors/amazon-sqs-store.png" title="Amazon SQS Connector Store" width="200" alt="Amazon SQS Connector Store"/>

## Compatibility

| Connector Version | Supported product versions                         | Supported API |
|-------------------|----------------------------------------------------|-------------|
| 2.0.0             | MI 4.3.0                                           |AWS SDK|
 | 1.1.1             | APIM 4.0.0, EI 7.1.0, EI 7.0.x, EI 6.6.0, EI 6.5.0 |REST|

For older versions, see the details in the connector store.

## Amazon SQS connector documentation(latest - 2.x version)

The WSO2 Amazon SQS connector allows you to access the exposed API through the integration runtime. Through this connector, you can perform CRUD operations for queues in Amazon SQS instance, update permissions and can work with messages. For further reference, please refer to [Amazon SQS API reference](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/APIReference/Welcome.html).

* **[Amazon SQS Connector Example]({{base_path}}/reference/connectors/amazonsqs-connector/2.x/amazonsqs-connector-2.x-example/)**: This example explains how to use the Amazon SQS Connector to create a queue in the Amazon SQS, send a message to the queue, forward it to a backend service and send the response to the user. 

* **[Amazon SQS Connector Reference]({{base_path}}/reference/connectors/amazonsqs-connector/2.x/amazonsqs-connector-2.x-reference/)**: This documentation provides a reference guide for the Amazon SQS Connector.

## Amazon SQS inbound endpoint

The AmazonSQS Inbound Endpoint allows you to connect to Amazon and consume messages form an Amazon SQS queue. The messages are then injected into the mediation engine for further processing and mediation.

* **[Amazon SQS Inbound Endpoint Example]({{base_path}}/reference/connectors/amazonsqs-connector/amazonsqs-inbound-endpoint-example/)**: This example demonstrates how the AmazonSQS inbound endpoint works as a message consumer. 

* **[Amazon SQS Inbound Endpoint Reference]({{base_path}}/reference/connectors/amazonsqs-connector/amazonsqs-inbound-endpoint-reference-configuration/)**: This documentation provides a reference guide for the Amazon SQS Inbound Endpoint.

## How to contribute

As an open source project, WSO2 extensions welcome contributions from the community. 

To contribute to the code for this connector, create a pull request in the following repositories. 

* [Amazon SQS connector GitHub repository](https://github.com/wso2-extensions/esb-connector-amazonsqs)
* [Amazon SQS inbound endpoint GitHub repository](https://github.com/wso2-extensions/esb-inbound-amazonsqs)

Check the issue tracker for open issues that interest you. We look forward to receiving your contributions.
