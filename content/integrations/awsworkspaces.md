---
title: Datadog-AWS Workspaces Integration
integration_title: AWS Workspaces
kind: integration
git_integration_title: amazon_workspaces
newhlevel: true
description: "Track failed connections, session latency, unhealthy workspaces, and more."
---

## Overview

Amazon WorkSpaces is a fully managed, secure desktop computing service which runs on the AWS cloud.

Enable this integration to see in Datadog all your Workspaces metrics.

## Setup
### Installation

If you haven't already, set up the [Amazon Web Services integration first](/integrations/aws). There are no other installation steps that need to be performed.

### Configuration

In the Amazon Web Services integration tile, ensure that Workspaces is checked under metric collection.

## Data Collected
### Metrics

{{< get-metrics-from-git >}}

Each of the metrics retrieved from AWS will be assigned the same tags that appear in the AWS console, including but not limited to host name, security-groups, and more.
