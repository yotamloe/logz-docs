---
layout: article
title: Reports
permalink: /user-guide/reports/
flags:
  logzio-plan: community
tags:
  - reports
contributors:
  - imnotashrimp
---

Logz.io Reports allows you to automatically generate reports
using your Kibana dashboards.
You can send reports on a regular schedule to Slack or email recipients.

To navigate to the Reports page:

* In your Operations account,
  select **Alerts & Events > Reports** in the top menu.
* In your Cloud SIEM account,
  click **Reports** in the top menu.

#### Configuring a report

<div class="tasklist">

##### Give your report a name and description

Your report's name will be shown as the email subject or Slack heading.

The description will be included in the message body.
It's a good idea to use the description to give some context
for why recipients are receiving the report.

##### Choose a dashboard and time range

Choose **Which dashboard to send** to your recipients.

Use **For this time range** to filter logs to be included in the report.

_For example_:
If you choose a time range of 24 hours on a report sent every Monday at 09:00,
each week's report will show a snapshot of your logs from 09:00 Sunday through 09:00 Monday.

Your time range can be anything from 1 minute to 30 days.

##### Set the schedule

Use the **Cron schedule** to set the frequency of your reports.

Logz.io uses quartz cron.
If you need help generating a cron expression, see
[Cron Expression Generator](https://www.freeformatter.com/cron-expression-generator-quartz.html#cronexpressionexamples/).

##### Choose the recipients

Use **Who to send it to** to choose the report's email and Slack recipients.

If you choose **Include a link to the live dashboard in the message**,
report recipients will have a quick link to the dashboard for the report's time range.

</div>
