# Supply Chain Analysis for a Fashion and Beauty Start-up

This repository presents a comprehensive supply chain analysis for a Fashion and Beauty start-up, conducted using Python and popular data analysis libraries such as Pandas and Plotly. The analysis provides valuable insights into various aspects of the supply chain, including product types, inventory management, shipping logistics, and customer demographics.

## Dataset

The analysis is based on a dataset containing supply chain data for various products, including haircare, skincare, and cosmetics. The dataset includes information such as product SKUs, prices, availability, sales figures, customer demographics, stock levels, lead times, order quantities, shipping details, supplier information, production volumes, manufacturing costs, inspection results, defect rates, transportation modes, and costs.

## Analysis Overview

The analysis covers the following key areas:

1. **Exploratory Data Analysis**: Gaining insights into the dataset by analysing missing values, location demographics, and product type distributions.

2. **Product and SKU Analysis**: Examining revenue generation, stock levels, and order quantities across different products and SKUs.

3. **Shipping and Logistics Analysis**: Evaluating shipping carriers, costs, and transportation mode efficiencies based on factors such as lead times and defect rates.

4. **Customer Demographics Analysis**: Understanding revenue patterns and customer preferences across different product types and demographics.

5. **Lead Time Analysis**: Assessing lead times by transportation mode and routes, identifying the most efficient options.

6. **Inventory Optimisation Analysis**: Implementing the Economic Order Quantity (EOQ) model to optimise inventory levels and order quantities.

7. **Supply Chain Risk Assessment**: Identifying high-risk products and areas within the supply chain based on factors such as lead times and stock levels.

## Key Findings and Recommendations

### Product and SKU Analysis

- The skincare product category accounts for the highest sales volume (45%), followed by haircare (29.5%) and cosmetics (25.5%).
- Certain SKUs, such as SKU0 and SKU18, exhibit significantly higher revenue generation compared to others, indicating potential opportunities for further investment or optimisation.
- Regular monitoring of stock levels and order quantities for top-performing SKUs is recommended to ensure adequate supply and avoid stockouts.

### Shipping and Logistics Analysis

- Carrier B generates the highest total revenue, highlighting its importance in the supply chain.
- The road transportation mode accounts for the highest transportation costs (30.3%), followed by rail (28.7%), air (27.6%), and sea (13.4%).
- While the sea transportation mode has the lowest defect rates (12.2%), it also has the highest average lead times, suggesting a potential trade-off between quality and speed.

### Customer Demographics Analysis

- Female customers contribute the highest revenue for cosmetics and haircare products, while male customers generate the highest revenue for skincare products.
- Non-binary and unknown customer demographics exhibit relatively lower revenue generation across all product types, indicating potential opportunities for targeted marketing campaigns.

### Lead Time Analysis

- The sea transportation mode offers the shortest average lead times, making it an attractive option for time-sensitive deliveries.
- Route A has the lowest average lead times across all routes, suggesting it could be prioritised for expedited shipments.

### Inventory Optimisation Analysis

- The analysis identifies SKUs where the order quantities deviate significantly from the calculated Economic Order Quantity (EOQ), indicating potential inefficiencies in inventory management.
- Implementing the EOQ model can help optimise inventory levels, reduce carrying costs, and improve overall supply chain efficiency.

### Supply Chain Risk Assessment

- Products like SKU68, SKU2, and SKU34 exhibit the highest risk scores based on their lead times and stock levels, warranting closer monitoring and risk mitigation strategies.
- Implementing risk assessment frameworks and contingency plans for high-risk products can help mitigate potential disruptions and ensure supply chain resilience.

## Future Enhancements

While this analysis provides valuable insights, there are several potential areas for future enhancements:

- Incorporating additional data sources, such as supplier performance metrics, manufacturing process data, and quality control data, could provide a more comprehensive view of the supply chain.
- Developing predictive models to forecast demand, optimise inventory levels, and identify potential bottlenecks or disruptions within the supply chain.
- Exploring advanced optimisation techniques, such as multi-objective optimisation or simulation-based optimisation, to balance conflicting objectives like cost, lead time, and quality.
- Integrating supply chain data with financial and operational data to enable end-to-end visibility and decision-making across the organisation.

## Getting Started

To run the analysis locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-repo-url.git`
2. Install the required Python packages: `pip install pandas plotly`
3. Navigate to the project directory: `cd supply-chain-analysis`
4. Open the Jupyter Notebook: `jupyter notebook Supply_Chain_Analysis.ipynb`

## Licence

This project is licensed under the [MIT Licence](LICENSE).
