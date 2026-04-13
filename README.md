# National AI Competitiveness: A Quantitative Policy Analysis

This repository contains a quantitative evaluation of global AI competitiveness, integrating data from the **Stanford AI Index** and the **Tortoise Global AI Index**. The project focuses on identifying the structural drivers of AI leadership to provide evidence-based policy recommendations for the Canadian innovation ecosystem.

## Project Summary
We developed a data-driven framework to quantify how national investments in talent, infrastructure, and research translate into global competitiveness. By contrasting Canada’s performance against top-tier nations, this study identifies specific gaps in the current Pan-Canadian AI Strategy—particularly regarding commercialization and hardware sovereignty.

## Data & Pre-processing
The analysis utilizes multi-modal datasets, including citation counts, private investment flows, and infrastructure metrics. We implemented a pipeline to normalize disparate global indices and utilized NLP techniques to extract structured data from national strategy reports, ensuring a consistent baseline for cross-country comparison.

## Technical Methodology
* **Feature Importance:** Used **Random Forest** regressors to determine which indicators (e.g., STEM graduates vs. compute capacity) most accurately predict a high competitiveness ranking.
* **Sentiment Analysis:** Performed NLP on national policy documents and social media to correlate government rhetoric with tangible investment outcomes and public perception.
* **Agentic Framework:** Developed an AI assistant using **CrewAI** to query our findings, providing a technical interface for navigating complex policy-data relationships.

## Policy Recommendations for Canada
* **Compute Sovereignty:** Shift from general research support toward dedicated hardware investments to reduce dependency on foreign infrastructure and secure domestic compute capacity.
* **Commercialization Pipeline:** Implement targeted tax credits and scaling incentives to help Canadian AI startups transition from academic research to global market deployment.
* **Skill Alignment:** Address current gaps in AI literacy by integrating practical implementation training into federally funded research and internship programs.

## Strategic Outlook
Our analysis suggests that while Canada remains a leader in research talent, long-term competitiveness depends on improving "Infrastructure" and "Operating Environment" scores. The findings provide a roadmap for policy adjustments aimed at maintaining Canada's position in a rapidly evolving geopolitical landscape.
