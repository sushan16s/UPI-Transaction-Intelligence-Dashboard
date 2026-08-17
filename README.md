# UPI 2024 Transaction Intelligence Dashboard

An interactive Power BI analytics solution for analyzing UPI transaction activity, customer behavior, banking performance, digital payment patterns, and fraud indicators across a 2024 transaction dataset.

## Project Overview

This project analyzes 250K+ UPI transactions with a total transaction value of ₹32.79 Cr. The dashboard converts transaction-level data into business-oriented KPIs and interactive visualizations to identify transaction trends, customer activity patterns, bank performance, payment behavior, and fraud-related patterns.

The dataset is a synthetic/analytical dataset created for data analytics and dashboard development purposes and does not represent official UPI transaction data.

## Business Objectives

- Monitor overall transaction volume and transaction value
- Analyze monthly transaction trends
- Identify high-performing states and merchant categories
- Understand customer transaction behavior by age, time, device, and transaction type
- Compare banking performance across sender and receiver banks
- Analyze bank transaction volume and market share
- Identify fraud transaction patterns and high-risk segments
- Track key operational and transaction KPIs

## Dashboard Structure

The Power BI solution consists of four analytical pages:

### 1. Executive Overview

Provides a high-level view of overall UPI transaction performance.

**Key KPIs**
- Total Transaction Value
- Total Transactions
- Average Transaction Value
- Success Rate
- Fraud Transactions
- Fraud Rate

**Key Analysis**
- Monthly Transaction Trend
- Transaction Value by State
- Merchant Category Performance
- Transaction Share by Device
- Peak Transaction Hour
- Leading Bank
- Most Used Device

### 2. Customer Analysis

Focuses on customer transaction behavior and usage patterns.

**Key Analysis**
- Customer Activity by Hour
- Transaction Type Distribution
- Transactions by Age Group
- Weekday vs Weekend Transactions
- Most Active Age Group
- Preferred Transaction Type
- Weekend Transaction Percentage
- Peak Transaction Hour
- Most Used Device

### 3. Banking Analysis

Evaluates transaction activity and performance across banks.

**Key Analysis**
- Top Sender Banks by Transaction Value
- Top Receiver Banks by Transaction Value
- Transaction Volume by Bank
- Bank Market Share
- Leading Bank
- Highest Transaction Value
- Average Transaction Value
- Bank-level transaction performance

### 4. Fraud Analysis

Analyzes fraud-related transaction patterns within the dataset.

**Key KPIs**
- Fraud Transactions
- Fraud Amount
- Fraud Rate
- High-Risk State
- High-Risk Bank

**Key Analysis**
- Top States by Fraud Transactions
- Top States by Fraud Amount
- Monthly Fraud Trend
- Fraud Distribution by Transaction Type
- Highest Fraud Amount
- Top Fraud Type
- Peak Fraud Month

## Key Insights

The dashboard highlights several analytical patterns, including:

- Maharashtra records the highest transaction value among the analyzed states.
- SBI leads the banking analysis by transaction volume and transaction value.
- Android accounts for the largest share of transactions by device.
- The 26–35 age group represents the most active customer segment.
- P2P is the dominant transaction type in the analyzed dataset.
- Transaction activity peaks around 7 PM–8 PM.
- Fraud analysis identifies Maharashtra as a high-risk state within the dataset.
- July records the highest monthly fraud transaction count in the analyzed period.

> These findings are specific to the dataset used in this project and should not be interpreted as official UPI industry statistics.

## Tools & Technologies

- **Microsoft Excel** – Data cleaning, validation, transformation, and preparation
- **Power BI** – Interactive dashboard development and business visualization
- **DAX** – KPI calculations, measures, and analytical metrics

## Data Preparation

The transaction dataset was prepared in Excel before being imported into Power BI.

Key preparation activities included:

- Data validation
- Data cleaning
- Handling inconsistent values
- Data transformation
- Column standardization
- Preparing analysis-ready transaction data

## DAX & KPI Development

DAX was used to create business metrics and analytical measures such as:

- Total Transaction Value
- Total Transaction Count
- Average Transaction Value
- Success Rate
- Fraud Transaction Count
- Fraud Rate
- Fraud Amount
- Market Share
- Peak Transaction Hour
- Weekend Transaction Percentage

## Dashboard Features

- Interactive slicers
- Cross-filtering
- KPI cards
- Drill-through analysis
- Interactive charts
- Date filtering
- State-level analysis
- Bank-level analysis
- Customer segmentation
- Fraud pattern analysis

## Project Structure

```text
UPI-2024-Transaction-Intelligence/
│
├── README.md
├── UPI_2024_Transaction_Intelligence.pbix
└── Dashboard/
    ├── 01-Executive-Overview.png
    ├── 02-Customer-Analysis.png
    ├── 03-Banking-Analysis.png
    └── 04-Fraud-Analysis.png