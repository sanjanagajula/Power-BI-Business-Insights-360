# Power BI Business Insights 360
Welcome to the **AtliQ Hardware Business Insights 360** project repository! This Power BI dashboard initiative is designed to provide a comprehensive view of business performance across Finance, Sales, Marketing, and Supply Chain domains. Built with real-world datasets and Power BI best practices, this project demonstrates how data can drive informed decisions and strategic growth.


## 📖 Project Overview
AtliQ Hardware, a rapidly growing player in the hardware industry, is embracing data analytics to stay ahead in a competitive market and enable data-driven decision-making. The Business Insights 360 project is a comprehensive Power BI initiative designed to deliver actionable insights across key business functions: Finance, Sales, Marketing, and Supply Chain.



## ✨ Project Aim
This project aims to empower AtliQ Hardware stakeholders with valuable insights by leveraging the capabilities of Power BI. By providing answers to critical business questions through robust data analysis and visualization, the project supports informed decision-making and strategic planning.
## 🛠️ Tools Used
| Tool             | Purpose                             |
|------------------|-------------------------------------|
| Excel / CSV      | Data preprocessing                  |
| SQL              | Data querying from MySQL DB         |
| Power Query      | Data transformation                 |
| Power BI Desktop | Report design and visualization     |
| DAX Studio       | File size and performance tuning    |



## 🗃️ Datasets Used
**Database Source**: MySQL

**Main Tables**:
- **fact_sales_monthly**: Actual sales quantity
- **fact_forecast_monthly**: Forecasted sales
- **freight_cost**: Logistics cost
- **manufacturing_cost**: Cost per product
- **gross_price**: Initial product price
- **pre_invoice_deductions** / **post_invoice_deductions**: Discounts & incentives

**Dimension Tables**:
- **dim_customer**: Markets, platforms, and channels
- **dim_product**: Division, categories, variants
- **dim_market**: Zones and regions

## 🏢 Company Background
- AtliQ Hardware, a prominent player in the computer products market, has strategically expanded its reach across global markets, engaging with customers through diverse channels, including retailers, direct sales, and distributors. 
- As part of this expansion, the company identified specific challenges within the American market, necessitating a deeper, data-driven approach to understand performance and inform strategic decisions.
- To address this need, AtliQ Hardware has established a dedicated analytics team focused on leveraging data to gain actionable insights.
## 🎯 Project Kick-Off: Setting the Stage for Success
The project kick-off session was like the green light at the start of a journey! It helped us get a clear picture of what we were trying to achieve and why it mattered. It was also a great chance to ask questions, clear up any confusion, and make sure everyone was on the same page before jumping into the real work.
## 🤔 Defining Success: Key Questions for Dashboard Development
A thorough assessment of key questions is crucial before developing the Power BI dashboard. These questions ensure the dashboard aligns with business needs and expectations, providing a solid roadmap for development:
- **Strategic Alignment**: What is the primary objective of this Power BI dashboard, and how does it align with AtliQ Hardware's overall business strategy?
- **Measurable Outcomes**: How will the success of this project be defined and measured? What specific metrics will indicate its impact?
- **Time and Resources**: What is the anticipated project timeline, and what resources (data, personnel, etc.) are essential for its successful completion?
- **Stakeholder Engagement**: Are there any expectations for stakeholder previews or prototypes before the final release?
- **Value Proposition**: What specific benefits and outcomes are stakeholders anticipating from the dashboard?
- **Risk Mitigation**: Are there any potential challenges or concerns that need to be addressed during development?
- **Target Audience**: Who are the primary users of this dashboard, and what specific purposes will they use it for?
- **User Expectations**: What are the stakeholders' expectations upon project completion in terms of functionality, impact, or benefits?
- **Design Preferences**: Has there been any specific input from stakeholders regarding the dashboard's design and layout?







## 📐 Data Modeling
A well-structured data model is the basis of any insightful report. In the Business Insights 360 project, significant effort went into meticulously crafting the data model. This recognized its crucial role in driving accurate and performant analytics.

**Why Data Modeling Matters**:
- **Foundation for Visuals**: The data model serves as the blueprint for all visuals and dashboards. A strong and accurately modeled structure ensures the visual representations of data are reliable and provide meaningful insights.
- **Optimizing Performance**: Poor data modeling can significantly hinder report responsiveness and overall performance. Implementing best practices and optimizing the model aimed to ensure efficient query execution and a smooth user experience.
- **Adherence to Best Practices**: Valuable guidelines from resources such as Addend Analytics' blog on data modeling best practices were used to inform the approach and create a model that is both effective and efficient.

![Screenshot 2025-06-02 162432](https://github.com/user-attachments/assets/6bd3c297-08d0-429e-9645-aaa93a9cd968)

**Embracing the Snowflake Schema**:
The Snowflake data modeling method was implemented for this project. This approach allows for:
- **Complex Relationships**: The Snowflake schema enables the representation of intricate relationships between data elements by normalizing dimension tables into sub-dimensions. This is beneficial for detailed analysis and deeper insights, notes Databricks.
- **Efficient Query Processing**: While potentially more complex than a star schema, the Snowflake schema can be highly effective in Power BI, especially when optimized with techniques like query folding, composite models, and appropriate storage modes. Snowflake architecture and design principles were leveraged to ensure efficient data processing.
- **Scalability**: The Snowflake schema can handle large and complex data models effectively, making it a suitable choice for enterprise-scale data analysis and reporting.


## 📊 Power BI Skills Acquired
- Created Date tables using M Language
- Designed interactive dashboards using Bookmarks and Buttons
- Built complex DAX measures and calculated columns
- Implemented conditional formatting and dynamic titles
- Validated data and created KPIs
- Published reports to Power BI Service with refresh scheduling

## 📌 Project Outcome: Empowering Decisions with Data – Business Insights 360
Completing the Business Insights 360 Power BI report was a major milestone in my data analytics journey. This project wasn’t just about building charts — it was about using data to help AtliQ Hardware make smarter, faster business decisions across departments like finance, sales, marketing, and supply chain.

## ✅ Helping AtliQ Make Informed Decisions
The dashboard I built allows stakeholders to shift from gut-feeling decisions to data-backed ones. With interactive visuals and filters, they can instantly track KPIs, compare performance across regions and markets, and make well-informed choices based on current trends and historical patterns.

## 🔎 Answering the “Why” Behind the Numbers
One of my goals was to go beyond just what is happening and focus on why it’s happening. Using DAX measures and slicers, I created tools that allow users to dive deep into insights like:

- Why sales dropped in a specific region

- What’s driving profitability

- Which product categories are performing best

- How forecasted demand compares to actual sales

## 📈 Covering Multiple Business Functions
The dashboard provides an end-to-end view of the business with dedicated pages for:

- Finance View – Profitability, net sales, gross margin

- Sales View – Monthly trends, product performance, regional sales

- Marketing View – Campaign impacts and customer segmentation

- Supply Chain View – Forecast vs actual demand, inventory performance

- Executive View – High-level KPIs for leadership

Each section was carefully designed to meet stakeholder needs, using Power BI best practices I learned in the Codebasics Power BI course.

## 🔄 Future-Ready and Easy to Update
The model follows a snowflake schema for better performance and scalability. It’s built to handle updates and grow with AtliQ’s future data needs. New data can be loaded easily from the MySQL database, and the visuals refresh accordingly.

