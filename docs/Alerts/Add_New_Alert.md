---
sidebar_position: 2
id: 'Add New Alert'
---

# Add New Alert

At present we offer only KPI related anomaly alerts. Event Alerts will be added soon.

![Alert Type](/img/Alerts/alerttype.png)

:::note
You will need to [configure alert channels](/Alerts/Alert_Destination.md) before setting up an alert.
:::

## KPI Alert

You need to fill in the following fields:

-   **Select KPI**: Select the KPI for which you want to set up the alert

-   **Name of your Alert**: Provide a name for the alert

-   **Alert Type**: Currently, you can only setup alerts for Anomaly Detection for a KPI.

-   **Severity Score**: You can select the Severity Score threshold above which you'll be sent an alert. If your data point is an anomaly and has a severity score 
    greater than your threshold, an alert will be sent.

-   **Alert Frequency**: How frequently will the alert be sent. Currently we offer Daily Alerts.

-   **Message Body**: This is the message you want accompanied when the alert is sent to you.

-   **Select Channel**: Channel on which you want to receive the alert at. Currently you can choose between either :

    -   Email: You can add recipient emails. Press enter after typing an email to add it to the list.

    -   Slack: You can select the channel to which the alert will be triggered.

-  **Send as**: Here you can select whether you want alerts to be sent individually (as soon as anomaly is computed) or as a daily consolidated report.

:::note
Consolidated [Reports need to be configured](/Alerts/Alert_Report_Settings.md) to receive them.
:::

![Add KPI alert](/img/Alerts/add_alert_1.png)

![Add KPI alert - channel config](/img/Alerts/add_alert_2.png)

