# Maji Ndogos Water Project Part3 Power BI
## Purpose
This Power BI report was developed to support national and provincial decision-makers in Maji Ndogo by providing clear, actionable insights into water access, challenges, and the cost of improvements. <br>
The report follows a structured narrative recommended by our mentor: <br>
1. Who are we doing this for, and where are they? <br>
2. What do we need to do, and where do we need to do it? <br>
3. What will this cost? <br>
This order ensures users first understand the population and challenges, then the required actions, and finally the financial implications.
## User Stories
### President Naledi:
- Understand overall water access in Maji Ndogo. <br>
- Identify how many people are affected and what challenges they face. <br>
- Know how much money is needed for upgrades and where it should be allocated. <br>
- Compare results nationally and provincially, with rural/urban splits.
### Provincial Leaders:
- Focus on province-specific data only. <br>
- Review town-level details: queues, gender composition, broken taps, and local challenges. <br>
- Access a summary of improvement costs for their province.
## Dashboard Pages
### National Overview
<img width="1190" height="740" alt="image" src="https://github.com/user-attachments/assets/d96702c4-7c24-49a8-89eb-4ae90186601e" />
<img width="1171" height="668" alt="image" src="https://github.com/user-attachments/assets/77c0efb9-0531-45ed-bc4e-425e69d57bef" />

### Provincial Pages (One per Province) 
- Province-specific population and access metrics <br>
- Town-level breakdowns (queues, gender, broken taps) <br>
- Budget per town and per improvement type <br>
- Drill-through from national page <br>
- Rural vs. urban splits <br>
- High-impact summary cards

 ### Financial / Budget Details
- National and provincial budget summaries. <br>
- Rural-adjusted costs (+50% for rural improvements). <br>
- Budget distribution visuals. <br>
- Pct of Province Budget (Improvement): Shows the proportion of each province’s budget dedicated to improvements:

### Key Measures & Calculations (DAX)
- Average_queue_time: Mean queue time per water source. <br>
- Basic_water_access: Classifies sources as Basic or Below Basic:<br>
-- Clean wells only (polluted excluded) <br>
-- Home taps classified as basic. <br>
-- Shared taps valid if queue <30 minutes. <br>
-- Contaminated wells, rivers, broken taps = Below Basic. <br>
- Rural_adjusted_cost: Adjusts rural improvements by +50%. <br>
- Budgeted_improvement_cost: Links improvements to costs, adjusted for rural vs. urban. <br>
- Access_once_complete: % of population with basic water access after upgrades. <br>
- Pct of Province Budget (Improvement): Shows proportion of provincial budget dedicated to improvements.
<img width="1173" height="675" alt="image" src="https://github.com/user-attachments/assets/6fc72723-2903-4c04-91a7-5a42d8ce0b11" />

<img width="1086" height="660" alt="image" src="https://github.com/user-attachments/assets/5ceaff89-63c1-47a1-a4b4-f8cbbb361f72" />

### Skills Applied
- Data modeling and transformation in Power BI. <br>
- Advanced DAX measures and conditional logic. <br>
- Data storytelling based on user stories. <br>
- Interactive visualization design (slicers, maps, bookmarks, drill-throughs, tooltips). <br>
- Impact analysis linking costs to measurable improvements in water access




