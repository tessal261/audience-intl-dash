# International Audience Dashboard

## Interactive Market Penetration & GPV Analysis

This dashboard provides a comprehensive analysis of market penetration, year-over-year growth, and GPV contribution by seller segment across four key markets: Canada, United Kingdom, Australia, and Japan.

### 🌐 **[View Live Dashboard](https://tessal261.github.io/audience-intl-dash/active_sellers_analysis.html)**

### 📊 **Alternative Views:**
- **[Active Sellers Analysis](https://tessal261.github.io/audience-intl-dash/active_sellers_analysis.html)** - Focus on sellers with recent payment activity
- **[Complete Market Analysis](https://tessal261.github.io/audience-intl-dash/complete_market_analysis.html)** - All registered merchants

### Key Features

- **Interactive Pie Charts**: Market share visualization for each country
- **Tabbed Data Views**: Switch between YoY Growth, GPV Share, and Average GPV per Merchant
- **Comprehensive Metrics**: Market penetration, growth trends, and revenue contribution
- **Color-coded Insights**: Visual indicators for positive/negative trends

### Key Findings

#### The Food & Drink Paradox
Despite representing only 7-9% of merchants in most markets, Food & Drink generates 31-52% of total GPV, indicating much higher transaction values per merchant.

#### Market-Specific Insights
- **Japan**: All segments showing explosive growth (23-47% YoY)
- **Australia/UK**: Food & Drink dominates GPV despite small market share
- **Canada**: Balanced growth across Services and Food & Drink
- **Retail**: Declining in mature markets (UK -12%, Australia -5%)

### Data Sources
- Merchant data from APP_BI.HEXAGON.VDIM_MERCHANT
- GPV data from APP_BI.HEXAGON.VAGG_DAILY_PROCESSING_SUMMARY
- Analysis period: Last 12 months

### Files
- `active_sellers_analysis.html` - **Primary dashboard** (active sellers only)
- `complete_market_analysis.html` - Alternative view (all registered merchants)
- `active_sellers_data.csv` - Active sellers data export
- `comprehensive_market_data.csv` - Complete market data export

---
*Generated using Snowflake data analysis and visualization tools*
