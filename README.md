# Intelligent Customer Support Ticket Management System Using Salesforce and Agentforce

## 1. Project Objective

The objective of this project is to develop an intelligent customer support ticket management system using Salesforce and Agentforce. The system automatically analyzes customer issues, determines ticket priority, assigns tickets to appropriate support agents, and creates follow-up tasks for critical issues.

The main goals are to reduce manual effort, improve response time, ensure consistent ticket prioritization, and provide better visibility to support managers.

---

## 2. Problem Statement

Customer support teams often handle a large number of tickets manually. This can lead to delays in identifying urgent issues, inconsistent priority classification, uneven workload distribution, and increased manual effort.

The proposed system addresses these challenges by automating ticket analysis, prioritization, assignment, and monitoring using Salesforce automation and Agentforce AI.

---

## 3. Salesforce Solution

A custom **Support Ticket** object is created in Salesforce to centrally store and manage customer service requests.

Important fields include:

* Ticket Number
* Customer Email
* Issue Description
* Priority
* Category
* Status
* Assigned Agent

Priority values are:

* High
* Medium
* Low

Status values can include:

* New
* In Progress
* Waiting for Customer
* Resolved
* Closed

---

## 4. Agentforce AI and Automation

Agentforce is used to analyze customer ticket information and identify the appropriate priority based on the issue description.

For example:

* **High:** Urgent, critical, system failure, service unavailable
* **Medium:** Error, performance issue, functionality problem
* **Low:** General questions or non-urgent requests

Salesforce Flow is used to automate the next steps, including updating the ticket, assigning an agent, and creating tasks.

---

## 5. Automatic Assignment and Task Creation

After analyzing a ticket, the system assigns it to the appropriate support agent based on the ticket category.

For High-priority tickets, Salesforce automatically creates a follow-up Task for the assigned agent.

Example:

**High Priority → Agent Assigned → Urgent Task Created**

This helps support teams identify and respond to critical customer issues quickly.

---

## 6. Reports, Dashboard, and Security

Salesforce Reports and Dashboards provide managers with visibility into support operations.

Important reports include:

* Tickets by Priority
* Tickets by Status
* Tickets by Category
* Tickets by Support Agent
* Open High-Priority Tickets

Security and permissions are configured so that support agents can work on tickets while managers can monitor tickets, workload, reports, and dashboards.

---

## 7. Expected Outcome and Benefits

The completed system provides an automated and centralized customer support process.

Expected benefits include:

* Faster identification of urgent tickets
* Reduced manual effort
* Consistent ticket prioritization
* Automatic ticket assignment
* Automatic follow-up task creation
* Improved workload visibility
* Faster customer response
* Better customer support management

The project demonstrates how **Salesforce and Agentforce AI** can be combined with automation to improve the efficiency and effectiveness of customer support operations.
# Customer-Support-Ticket-Priority-Prediction-and-Automation
