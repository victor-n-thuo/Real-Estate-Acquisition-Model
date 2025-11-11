# Real Estate Investment Pro Forma & Valuation Model: West Ridge North Acquisition Analysis

## Project Background & Overview

This project simulates a core task for a Financial Planning & Analysis (FP&A) or investment analyst at a real estate private equity firm.

**Fictional Context:** As an analyst for **"Summit Real Estate Partners,"** I was tasked with evaluating a potential acquisition: "West Ridge North," an 80-unit apartment community. The objective was to build a comprehensive 10-year pro forma financial model to determine the project's financial viability and potential returns.

**Stakeholders:** The analysis and recommendations are prepared for Summit's Investment Committee, which includes the Chief Financial Officer (CFO) and Managing Partners.

**Business Problem:** The committee needs a data-driven recommendation on whether to proceed with the acquisition of West Ridge North. The decision hinges on key profitability metrics, primarily the Internal Rate of Return (`IRR`) and Net Present Value (`NPV`), and an understanding of the investment's sensitivity to key market assumptions like rent growth.

## Executive Summary

The analysis strongly supports proceeding with the acquisition of the West Ridge North property. The model projects an **unlevered Internal Rate of Return (IRR) of 29.78%**, which significantly exceeds our firm's benchmark hurdle rate of 20%.

The project generates a **Net Present Value (NPV) of $7.39 million**, indicating substantial value creation. Sensitivity and scenario analyses reveal that while the investment's profitability is sensitive to initial rent levels and annual rent growth, it remains profitable even under more conservative assumptions. The primary recommendation is to move forward with deeper due diligence, focusing on validating market rent comparables and the operational plan to increase occupancy to 95% within the first two years.

## Tools & Technologies

*   **Primary Tool:** Microsoft Excel
*   **Key Excel Functions & Features:**
    *   Dynamic 10-Year Pro Forma Cash Flow Modeling
    *   `NPV`, `IRR`, `XNPV`, and `XIRR` functions for investment valuation
    *   Two-Variable Data Tables for **Sensitivity Analysis**
    *   **Scenario Manager** for comparing base-case vs. optimistic outcomes
    *   Advanced logical functions (`IF`, Nested `IF`s)
    *   Data structuring and professional formatting

## Model Structure & Methodology

The analysis is built on a 10-year discounted cash flow (DCF) model structured to professional standards.

1.  **Inputs & Assumptions:** A centralized section captures all key drivers, including acquisition details (Purchase Price, Cap Rate), operational assumptions (Rent Growth, Cost Growth), and sale details (Holding Period, Exit Cap Rate). This allows for easy modification and stress-testing.

2.  **Cash Flow Pro Forma:**
    *   **Revenue:** Calculated from Net Potential Rent, factoring in assumptions for vacancy and delinquency.
    *   **Operating Expenses:** Itemized expenses including Repairs & Maintenance, Salaries, and Taxes are projected forward based on a cost growth percentage.
    *   **Net Operating Income (NOI):** The primary measure of a property's profitability (Total Rental Income - Total Operating Expenses).
    *   **Capital Expenditures:** Includes the initial property purchase and a significant Year 1 renovation budget of $2 million.
    *   **Net Cash Flow:** The final unlevered cash flow for each year, including the net proceeds from the property sale in Year 10.

3.  **Valuation & Returns:**
    *   **Sale Price (Reversion Value):** Calculated by applying an Exit Cap Rate of 5.00% to the projected Year 10 Net Operating Income.
    *   **Profit Metrics:** The model calculates `IRR`, `NPV`, `ROI`, and their date-sensitive counterparts (`XIRR`, `XNPV`) to provide a comprehensive view of the investment's attractiveness.

## Insights Deep Dive: Profitability, Risk, and Scenario Analysis

### 1. Strong Core Profitability

The primary analysis confirms this is a highly attractive investment opportunity.

*   **Internal Rate of Return (IRR):** The projected **`IRR` of 29.78%** is well above the 20% benchmark rate, indicating the project's returns are more than sufficient to compensate for the risk involved.
*   **Net Present Value (NPV):** With a discount rate of 20%, the project yields a positive **`NPV` of $7.39 million**. This means the present value of all future cash inflows exceeds the initial investment by over $7M, representing direct value creation for the firm.



### 2. Sensitivity to Market Conditions

A two-variable data table was created to analyze how the Year 10 Net Operating Income (a key driver of sale price) changes based on two critical assumptions: **Initial Monthly Rent** and **Annual Rent Growth %**.

*   **Key Finding:** The model is highly sensitive to these two inputs. The base case projects a Year 10 NOI of **$2.95M** (with 5.00% growth and $2,300 starting rent).
*   **Impact Example:** If the annual rent growth is only 2.50% instead of 5.00%, the Year 10 NOI would fall to **$2.59M** (assuming $2,500 starting rent), a decrease of over 20% from the equivalent 5.00% growth scenario ($3.25M). This highlights the critical importance of validating long-term market growth projections.

 

### 3. Scenario Planning: "Expected" vs. "High Rent"

Excel's Scenario Manager was used to compare the base case ("Expected Rent") with a more optimistic "High Rent" scenario (8.00% rent growth and $2,500 starting rent).

*   **Key Finding:** The "High Rent" scenario results in a Year 10 NOI of **$4.21 million**, a **42% increase** over the base case NOI of $2.95 million. This demonstrates the significant upside potential if market conditions are more favorable than initially projected.

 

## Strategic Recommendations

Based on the financial model and analysis, the following recommendations are presented to the Investment Committee:

1.  **Proceed with Acquisition:** The project's financial metrics (29.78% IRR, $7.39M NPV) are robust and compelling. The investment is financially sound and aligns with the firm's return targets.
2.  **Conduct Rigorous Due Diligence on Rent Assumptions:** Given the model's sensitivity to rent growth and initial rent levels, the next phase should focus on validating these assumptions through third-party market reports and analysis of comparable properties.
3.  **Validate the Operational Turnaround Plan:** The model assumes occupancy increases from 75% to a stabilized 95% after the Year 1 renovations. The operational team's plan to achieve this should be scrutinized to ensure it is realistic and achievable within the projected timeframe.

## Links to Work

*   [**Excel Model File 1:** Pro Forma with Sensitivity & Scenario Analysis](./Model%20with%20scenario%20and%20sensitivity.xlsx)
*   [**Excel Model File 2:** NPV & IRR Valuation Analysis](./NPV,%20IRR,%20XIRR,%20XNPV.xlsx)
