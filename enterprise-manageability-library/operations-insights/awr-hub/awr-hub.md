# AWR Hub

## Introduction

In this lab, you will go through the process to navigate thru **AWR Hub**.

The Operations Insights AWR Hub lets you consolidate and store detailed performance data from the Automatic Workload Repository (AWR) of your important Oracle Databases. This consolidated AWR Hub allows you to view and analyze historical performance data beyond the AWR retention period of the source database.

An AWR report contains performance statistics on database activity between two points in time – two snapshots. This can be used for problem detection and self-tuning purposes. For example, you can compare database statistics captured during a period of poor performance and compare it with normal baseline performance to identify and diagnose problems. Because AWR Hub stores AWR snapshots for multiple databases, you can easily compare performance statistics across your database fleet.

Estimated Time: 20 minutes

### Objectives

-   Navigate thru AWR Hub.

### Prerequisites

This lab assumes you have completed the following labs:
* Lab: Enable Demo Mode

## Task 1: AWR Hub

1.  On the **Operations Insights Overview** page, from the left pane click **AWR-Hub**.

      ![Left Pane](./images/awr-hub.png " ")

2.  This will take you to **AWR Hub** page, which lists the Databases providing AWR snapshots.

      ![Left Pane](./images/awr-hub1.png " ")

3.  Click **More** (vertical ellipses) in the last column to display the pop-up menu and select **Generate AWR Report**.

      ![Left Pane](./images/awr-hub2.png " ")

4.  The **Generate Automatic Workload Repository Report** dialog appears. Selecting a different **Snapshot Start Time** changes the list of available snapshots for the **Start Snapshot** and **End Snapshots** drop-down menus. Select **Snapshot Start Time** and then **Start Snapshot** and **End Snapshots**. Click **Download**.

      ![Left Pane](./images/awr-hub3.png " ")

5.  Click **Save File** to save the AWR report on your local machine.

      ![Left Pane](./images/awr-hub4.png " ")

## Acknowledgements

- **Author** - Vivek Verma, Master Principal Cloud Architect, North America Cloud Engineering
- **Contributors** - Vivek Verma, Sriram Vrinda, Derik Harlow
- **Last Updated By/Date** - Vivek Verma, May 2022