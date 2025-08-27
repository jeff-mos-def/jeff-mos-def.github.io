---
title: Control Chart
draft: false
date: 2025-08-26
tags:
  - quality-management
  - data-analysis
  - process-improvement
  - seven-basic-quality-tools
---

A **Control Chart** is a graph used to study how a process changes over time. It is a run chart with the addition of statistically calculated upper and lower control limits. Its primary purpose is to determine if a process is stable and in a state of statistical control, or if there is special cause variation that needs to be investigated.

## **Key Aspects of a Control Chart**
- **Statistical Control** – It is the primary tool used to determine if a process is stable and predictable.
- **Common vs. Special Cause Variation** – It helps distinguish between normal, inherent process variation (common cause) and variation from specific, assignable events (special cause).
- **Control Limits** – These are the key feature, typically set at +/- 3 standard deviations from the mean. They represent the expected range of variation.
- **Rule of Seven** – A common guideline suggesting that if seven or more consecutive data points fall on one side of the mean, it indicates a non-random pattern that should be investigated.

## **How to Read a Control Chart**
| **Component** | **Description** | **Purpose** |
|---|---|---|
| **Center Line (Mean)** | The average of the historical process data. | Represents the central tendency or average performance of the process. |
| **Upper Control Limit (UCL)** | A horizontal line plotted above the mean, typically at +3 standard deviations. | Defines the upper boundary of expected random variation. |
| **Lower Control Limit (LCL)**| A horizontal line plotted below the mean, typically at -3 standard deviations. | Defines the lower boundary of expected random variation. |
| **Data Points** | Individual measurements plotted in sequence. | Show the actual performance of the process over time. |

A process is considered "out of control" if a data point falls outside the control limits or if non-random patterns (like the Rule of Seven) are observed.

## **Example Scenarios**

### **Manufacturing**
A factory uses a control chart to monitor the diameter of a manufactured bolt. If a data point falls above the UCL, it might indicate a machine is out of calibration (a special cause), prompting an immediate investigation.

### **IT Service Desk**
An IT department tracks the time it takes to resolve support tickets. A control chart helps them see if their resolution time is stable and predictable. If a new point falls below the LCL (meaning an unusually fast resolution), they might investigate to see if a new, positive technique was used that can be replicated.

## **Why Control Charts Matter**
- **Prevents Overreaction** – They stop managers from reacting to normal, random process fluctuations (common cause variation) as if they were real problems.
- **Provides Process Stability Insights** – It is the best tool to know if your process is stable and predictable, which is a prerequisite for any meaningful process improvement.
- **Identifies Problems Objectively** – It uses statistical data to signal when a problem has occurred, removing guesswork and opinion.
- **Drives Data-Driven Decisions** – It provides a clear, visual basis for making decisions about when to intervene in a process and when to leave it alone.

See also: [[Run Chart]], [[Seven Basic Quality Tools]], [[Quality Management]], [[Statistical Process Control (SPC)]].