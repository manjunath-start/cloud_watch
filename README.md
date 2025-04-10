# AWS CloudWatch

## What is AWS CloudWatch?
Amazon CloudWatch is a monitoring and observability service for AWS resources and applications. It collects and tracks metrics, monitors log files, and sets alarms based on thresholds to keep your infrastructure running smoothly.

### Features of AWS CloudWatch:
- **Monitoring Metrics**: Tracks resource usage, application performance, and operational health.
- **Alarms**: Notifies you when a metric exceeds a defined threshold.
- **Logs**: Aggregates and analyzes log data from different AWS services.
- **Dashboards**: Provides visual insights into your AWS environment.
- **Events**: Detects system changes and responds automatically.

## CloudWatch Alarm Example (Monitoring CPU Usage)
This repository contains a guide on how to **launch an EC2 instance** and set up CloudWatch alarms to monitor CPU utilization.

### Steps to Set Up an Alarm:
1. **Launch an EC2 instance** in AWS.
2. **Enable CloudWatch monitoring** in the instance settings.
3. **Create an alarm** to notify when CPU usage exceeds 60% for 5 minutes.
4. **Receive notifications** via Amazon SNS when the threshold is breached.

For detailed step-by-step instructions, refer to the included **"Launch an EC2 Instance.pdf"**.
