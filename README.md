<div align="center">

# Customer Intelligence & Recommendation System

### RFM Segmentation · Behavioral Analytics · Product Recommendation · Retail Intelligence

**End-to-End Customer Analytics Platform for Data-Driven Retail Decision Support**

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![RFM](https://img.shields.io/badge/RFM-Customer%20Analytics-7C3AED?style=flat-square)

<br>

![Segmentation](https://img.shields.io/badge/CUSTOMER-SEGMENTATION-2563EB?style=for-the-badge)
![Recommendation](https://img.shields.io/badge/PRODUCT-RECOMMENDATION-D97706?style=for-the-badge)
![Deployment](https://img.shields.io/badge/DEPLOYMENT-LIVE-22C55E?style=for-the-badge&logo=streamlit&logoColor=white)

<br><br>

**Segment → Understand → Recommend → Act**

<br>

[![Launch Application](https://img.shields.io/badge/LAUNCH-LIVE%20APPLICATION-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://mwildannabila-customer-analytics.streamlit.app/)

</div>

---

## Project at a Glance

<table>
<tr>
<td align="center" width="20%">
<strong>RFM</strong><br>
Customer Segmentation
</td>
<td align="center" width="20%">
<strong>3 Dimensions</strong><br>
Recency · Frequency · Monetary
</td>
<td align="center" width="20%">
<strong>Behavioral</strong><br>
Customer Intelligence
</td>
<td align="center" width="20%">
<strong>Product</strong><br>
Recommendation
</td>
<td align="center" width="20%">
<strong>Live</strong><br>
Streamlit App
</td>
</tr>
</table>

> **Project focus:** Transforming retail transaction data into interpretable customer segments, behavioral insights, product recommendations, and actionable marketing intelligence.

---

# Business Problem

Retail transaction data contains valuable information about **who buys, how often they buy, how recently they purchased, and how much value they generate**.

Yet raw transaction records alone provide limited support for customer strategy.

A business needs to move from:

```text
Transactions
     │
     ▼
"What did customers buy?"
```

toward:

```text
Transactions
     │
     ▼
Customer Behavior
     │
     ├── Who are the most valuable customers?
     │
     ├── Who has become less engaged?
     │
     ├── How frequently do customers purchase?
     │
     └── Which products may be relevant?
     │
     ▼
Customer Intelligence
```

This project develops an end-to-end analytical system designed to bridge that gap.

---

# Live Application

<div align="center">

[![Open Dashboard](https://img.shields.io/badge/OPEN-CUSTOMER%20INTELLIGENCE%20SYSTEM-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://mwildannabila-customer-analytics.streamlit.app/)

</div>

The deployed application integrates:

`Customer Segmentation` · `RFM Analytics` · `Behavioral Analysis` · `Product Insights` · `Interactive Visualization`

into a single analytical interface.

---

# Dashboard Preview

<p align="center">
  <img src="assets/dashboard-overview.png" alt="Customer Intelligence Dashboard" width="900">
</p>

The dashboard provides an interactive overview of customer composition, purchasing behavior, segment distribution, and product-level insights.

<table>
<tr>
<td align="center" width="25%">
<strong>Customer</strong><br>
Overview
</td>
<td align="center" width="25%">
<strong>RFM</strong><br>
Segmentation
</td>
<td align="center" width="25%">
<strong>Behavior</strong><br>
Analysis
</td>
<td align="center" width="25%">
<strong>Product</strong><br>
Intelligence
</td>
</tr>
</table>

---

# Dataset & Analytical Scope

| Dimension | Scope |
|---|---|
| **Dataset type** | Retail Transaction Data |
| **Primary entity** | Customer |
| **Core variables** | Customer ID · Invoice Date · Quantity · Unit Price |
| **Engineered features** | Recency · Frequency · Monetary |
| **Segmentation** | RFM-Based |
| **Example segments** | High Value · Regular · At Risk |
| **Product layer** | Recommendation & Product Analysis |
| **Application** | Interactive Streamlit Dashboard |

Transaction-level records are transformed into customer-level behavioral features before segmentation and recommendation analysis.

---

# Customer Intelligence Architecture

```text
                    RETAIL TRANSACTIONS
                           │
                           ▼
                  Data Validation
                           │
                           ▼
               Cleaning & Preprocessing
                           │
                           ▼
                  Feature Engineering
                           │
                           ▼
                     RFM ANALYSIS
                           │
             ┌─────────────┼─────────────┐
             ▼             ▼             ▼
          RECENCY       FREQUENCY      MONETARY
             │             │             │
             └─────────────┼─────────────┘
                           ▼
                     RFM SCORING
                           │
                           ▼
                CUSTOMER SEGMENTATION
                           │
              ┌────────────┴────────────┐
              ▼                         ▼
      BEHAVIORAL ANALYSIS      PRODUCT INTELLIGENCE
              │                         │
              └────────────┬────────────┘
                           ▼
                 CUSTOMER INSIGHTS
                           │
                           ▼
                STREAMLIT DASHBOARD
                           │
                           ▼
                  DECISION SUPPORT
```

The architecture converts granular transactions into a customer-level analytical representation that is easier to interpret and operationalize.

---

# RFM Segmentation

RFM summarizes customer behavior using three dimensions:

<table>
<tr>
<td align="center" width="33%">

### Recency

**How recently did the customer purchase?**

Lower recency generally indicates more recent engagement.

</td>
<td align="center" width="33%">

### Frequency

**How often does the customer purchase?**

Higher frequency indicates repeated purchasing behavior.

</td>
<td align="center" width="33%">

### Monetary

**How much value has the customer generated?**

Higher monetary value indicates greater historical spending.

</td>
</tr>
</table>

Conceptually:

```text
                  CUSTOMER
                      │
          ┌───────────┼───────────┐
          ▼           ▼           ▼
       RECENCY     FREQUENCY    MONETARY
          │           │           │
          └───────────┼───────────┘
                      ▼
                   RFM SCORE
                      │
                      ▼
               CUSTOMER SEGMENT
```

This provides an interpretable alternative to treating all customers as a homogeneous population.

---

# Customer Segmentation

<div align="center">

![High Value](https://img.shields.io/badge/HIGH%20VALUE-Prioritize%20Relationship-7C3AED?style=for-the-badge)
![Regular](https://img.shields.io/badge/REGULAR-Grow%20Engagement-2563EB?style=for-the-badge)
![At Risk](https://img.shields.io/badge/AT%20RISK-Re--engage-D97706?style=for-the-badge)

</div>

| Segment | Behavioral Interpretation | Potential Strategy |
|---|---|---|
| **High Value** | Strong historical customer value | Relationship maintenance and loyalty |
| **Regular** | Consistent purchasing behavior | Engagement and value development |
| **At Risk** | Reduced recent engagement under the RFM rules | Re-engagement analysis |

> **At Risk** is an RFM-derived behavioral segment. It should not automatically be interpreted as a confirmed churn label.

This distinction is important because RFM measures purchasing behavior rather than directly observing future churn.

---

# Customer Overview

<p align="center">
  <img src="assets/customer-overview.png" alt="Customer Analytics Overview" width="880">
</p>

Customer-level aggregation provides a clearer view of how purchasing activity and revenue contribution vary across the customer base.

The analysis can reveal:

- Revenue concentration
- Differences in purchasing frequency
- Recent versus inactive customers
- High-value customer groups
- Uneven customer contribution

---

# Segment Distribution

<p align="center">
  <img src="assets/segment-distribution.png" alt="Customer Segment Distribution" width="820">
</p>

Segment distribution helps determine how the customer base is divided across different behavioral profiles.

Instead of viewing all customers equally:

```text
ALL CUSTOMERS
      │
      ▼
 RFM PROFILING
      │
 ┌────┼────────────┐
 ▼    ▼            ▼
HIGH  REGULAR    AT RISK
VALUE
 │      │            │
 ▼      ▼            ▼
Retain  Develop   Re-engage
```

This creates a more differentiated foundation for customer strategy.

---

# Customer Behavior Map

<p align="center">
  <img src="assets/behavior-map.png" alt="Customer Behavioral Map" width="880">
</p>

The behavior map provides a visual representation of differences across customer groups.

This allows patterns in:

`Recency` · `Purchase Frequency` · `Customer Value`

to be interpreted jointly rather than as isolated metrics.

---

# Product Recommendation

<p align="center">
  <img src="assets/recommendation.png" alt="Product Recommendation Analytics" width="880">
</p>

The recommendation layer extends the analysis from:

```text
WHO is the customer?
```

to:

```text
WHAT products may be relevant?
```

Product-level transaction patterns are used to generate recommendation-oriented insights that can support cross-selling and customer engagement analysis.

> The current recommendation component should be interpreted according to the implemented recommendation logic. It is not described as collaborative filtering or a machine-learning recommender unless those algorithms are actually implemented.

---

# Key Analytical Insights

## 01 · Customer Value Is Unevenly Distributed

Revenue contribution is concentrated among a smaller group of higher-value customers.

This indicates that customer-level revenue should be analyzed as a distribution rather than relying only on aggregate sales figures.

**Potential implication:** high-value customer relationships may warrant differentiated retention and loyalty strategies.

---

## 02 · Reduced Engagement Can Be Identified Through Recency

Customers with weaker recent purchasing activity can be isolated through RFM-based segmentation.

This provides a transparent signal for identifying customers who may warrant re-engagement analysis.

**Potential implication:** recency-based monitoring can help prioritize reactivation campaigns.

---

## 03 · Purchase Frequency Reveals Engagement Differences

Purchasing frequency varies across the customer population.

Repeated buyers and infrequent buyers therefore represent different behavioral profiles and may require different engagement strategies.

---

## 04 · Product Intelligence Extends Customer Segmentation

Segmentation identifies **who** different customers are behaviorally.

Product analysis adds another dimension by investigating **what** may be relevant to those customers.

Together:

```text
CUSTOMER INTELLIGENCE
        │
        ├── WHO?
        │     └── RFM Segment
        │
        ├── HOW?
        │     └── Purchase Behavior
        │
        └── WHAT?
              └── Product Recommendation
```

This produces a more complete customer-analytics workflow than segmentation alone.

---

# From Transactions to Customer Strategy

```text
                       TRANSACTIONS
                            │
                            ▼
                     CUSTOMER PROFILE
                            │
              ┌─────────────┼─────────────┐
              ▼             ▼             ▼
           Recency       Frequency      Monetary
              │             │             │
              └─────────────┼─────────────┘
                            ▼
                      RFM SEGMENT
                            │
               ┌────────────┴────────────┐
               ▼                         ▼
       CUSTOMER BEHAVIOR          PRODUCT INSIGHT
               │                         │
               └────────────┬────────────┘
                            ▼
                    MARKETING CONTEXT
                            │
                            ▼
                     BUSINESS ACTION
```

The project therefore moves beyond descriptive retail reporting toward **customer-oriented decision support**.

---

# Decision-Support Framework

| Analytical Signal | Potential Business Use |
|---|---|
| High monetary value | Loyalty and relationship prioritization |
| High purchase frequency | Engagement and cross-selling analysis |
| Increasing recency | Re-engagement consideration |
| High-value segment | Retention prioritization |
| Regular segment | Customer development strategy |
| At-risk RFM segment | Reactivation analysis |
| Product purchasing patterns | Recommendation and cross-selling context |

> These represent **potential applications of the analytical outputs**, not experimentally measured improvements in retention or revenue.

---

# Key Technical Challenge

### Challenge

Retail transaction data often contains strongly skewed customer spending and purchasing patterns.

A small number of customers can contribute disproportionately large monetary values, making fixed segmentation thresholds sensitive to the underlying distribution.

### Approach

The project uses **quantile-based RFM scoring** to derive interpretable relative customer profiles.

```text
Raw RFM Values
      │
      ▼
Distribution Analysis
      │
      ▼
Quantile-Based Scoring
      │
      ▼
R + F + M Profile
      │
      ▼
Customer Segment
```

This approach makes segmentation relative to the observed customer population while retaining straightforward business interpretation.

---

# Why Interpretability Matters

Customer segmentation becomes more useful when business stakeholders can understand **why a customer belongs to a particular segment**.

RFM provides this transparency:

```text
Customer A
│
├── Recent purchase
├── Frequent purchases
└── High monetary value
        │
        ▼
   HIGH VALUE
```

Rather than producing an opaque segment label, the framework maintains a direct relationship between customer behavior and segment assignment.

---

# Technology Ecosystem

<div align="center">

<img src="https://skillicons.dev/icons?i=python" height="48" alt="Python">
&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/numpy/013243" height="44" alt="NumPy">
&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/pandas/150458" height="44" alt="Pandas">
&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/plotly/3F4F75" height="44" alt="Plotly">
&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/streamlit/FF4B4B" height="44" alt="Streamlit">
&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/github/ffffff" height="44" alt="GitHub">

<br><br>

`Python` · `Pandas` · `NumPy` · `RFM Analysis` · `Plotly` · `Streamlit`

</div>

---

# Technical Stack

| Layer | Technology |
|---|---|
| **Programming** | Python |
| **Data Processing** | Pandas · NumPy |
| **Feature Engineering** | RFM |
| **Customer Segmentation** | Quantile-Based RFM Scoring |
| **Product Analytics** | Recommendation-Oriented Analysis |
| **Visualization** | Plotly |
| **Application** | Streamlit |
| **Deployment** | Streamlit Community Cloud |

---

# Skills Demonstrated

<table>
<tr>
<td width="33%" valign="top">

**Data Analytics**

- Data Cleaning
- Feature Engineering
- Behavioral Analysis
- Customer Profiling

</td>
<td width="33%" valign="top">

**Customer Intelligence**

- RFM Analysis
- Customer Segmentation
- Product Analytics
- Recommendation Logic

</td>
<td width="33%" valign="top">

**Analytics Engineering**

- Interactive Visualization
- Dashboard Development
- Data Storytelling
- Streamlit Deployment

</td>
</tr>
</table>

---

# Project Ownership

This is an **independent end-to-end project** developed across the complete analytical workflow.

### Muhammad Wildan Nabila
**Data Science · Customer Analytics**

Responsibilities included:

- Data cleaning and preprocessing
- Customer-level feature engineering
- RFM calculation and scoring
- Segmentation design
- Behavioral analysis
- Product recommendation logic
- Interactive visualization
- Streamlit application development
- Deployment
- Technical documentation

This end-to-end ownership demonstrates the ability to move from **raw transactional data to a deployed analytical application**.

---

# Analytical Limitations

The system should be interpreted within the scope of the implemented analytical methodology.

### RFM is retrospective

RFM describes historical purchasing behavior. It does not directly predict future churn or customer lifetime value.

### Relative segmentation

Quantile-based scoring depends on the observed customer distribution. Segment thresholds may change when applied to another dataset or time period.

### At Risk ≠ confirmed churn

Reduced purchasing recency can indicate disengagement, but it does not establish that a customer will churn.

### Recommendation scope

Recommendation quality depends on the implemented product recommendation logic and available transaction history.

### Business outcomes are not measured

The project does not demonstrate causal improvements in retention, conversion, or revenue from applying the recommendations.

These limitations are important when translating analytical outputs into business decisions.

---

# Future Development

Potential extensions include:

- Collaborative filtering
- Content-based recommendation
- Hybrid recommendation systems
- Customer Lifetime Value prediction
- RFM vs. K-Means comparison
- Churn prediction integration
- Market basket analysis
- Association-rule mining
- Recommendation evaluation metrics
- Customer cohort analysis
- Automated data pipelines
- CRM integration
- Recommendation API
- Model and customer-behavior monitoring

A particularly valuable extension would connect three analytical layers:

```text
SEGMENTATION
Who is the customer?
      │
      ▼
PREDICTION
What might the customer do?
      │
      ▼
RECOMMENDATION
What should we potentially offer?
```

This would evolve the project from descriptive customer intelligence toward a more comprehensive personalization system.

---

# Repository Structure

```text
customer-intelligence/
│
├── assets/
│   ├── dashboard-overview.png
│   ├── customer-overview.png
│   ├── recommendation.png
│   ├── segment-distribution.png
│   └── behavior-map.png
│
├── data/
├── notebooks/
├── src/
│
├── app.py
├── requirements.txt
├── LICENSE
└── README.md
```

---

# Run Locally

```bash
git clone <repository-url>
cd customer-intelligence

pip install -r requirements.txt
streamlit run app.py
```

---

# Project Summary

| Dimension | Implementation |
|---|---|
| **Business Problem** | Customer understanding and marketing prioritization |
| **Data** | Retail Transactions |
| **Primary Method** | RFM Analysis |
| **Features** | Recency · Frequency · Monetary |
| **Segmentation** | Quantile-Based RFM |
| **Example Segments** | High Value · Regular · At Risk |
| **Additional Layer** | Product Recommendation |
| **Visualization** | Interactive Plotly |
| **Application** | Streamlit |
| **Deployment** | **Live** |
| **Primary Value** | Customer Intelligence & Decision Support |

---

# Explore the Project

<div align="center">

[![Live Application](https://img.shields.io/badge/STREAMLIT-Live%20Application-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://mwildannabila-customer-analytics.streamlit.app/)

</div>

---

# Author

**Muhammad Wildan Nabila**  
Bachelor of Informatics · Universitas Muhammadiyah Malang

<div align="left">

![Data Science](https://img.shields.io/badge/Data%20Science-2563EB?style=flat-square)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-7C3AED?style=flat-square)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-0F766E?style=flat-square)
![Customer Analytics](https://img.shields.io/badge/Customer%20Analytics-D97706?style=flat-square)

</div>

---

<div align="center">

### Transaction Data → Customer Segmentation → Product Intelligence → Business Action

**Customer Analytics · RFM · Recommendation · Interactive Decision Support**

</div>
