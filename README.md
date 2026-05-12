# Risk_Assessment_Tool
Here's the README pulled directly from the document's own language:

NLNB IT Risk Assessment Tool
ETI 302 | Penn State University | Team GRQ

**Project Overview**
Nittany Lion National Bank (NLNB) is a financial institution that integrates hybrid-cloud technology with its operation. Despite its adoption of high-level technology, the bank experienced multiple application failures and system outages, which exposed vulnerabilities within the infrastructure. These failures resulted in major financial losses and reputational damage, especially coupled with competitive pressure from other banking institutions at the national level. As a response, our consulting team developed an all-encompassing IT risk assessment tool designed to evaluate emerging risks across the company's applications and data architectures, zero in on high-impact vulnerabilities, and provide specific recommendations to execute the goal of resilience and regulatory compliance.

**What the Tool Does**

The tool works by walking the client through a list of 25 diagnostic questions covering three categories: business, operational, and technical. On the business category side, it measures exposure to transaction disruptions, revenue loss, single points of failure, and compliance gaps across regulations like the FDIC. On the operational side, it looks at outages, incident response readiness, staffing, backup effectiveness, and third-party vendor concentration and contract risk. On the technical side, it evaluates legacy systems, patching, cybersecurity controls, cloud design, system integration weaknesses, and the organization's readiness to support future initiatives like AI adoption and cloud migration. While answering these questions, each answer is assigned a score, where "low" is scored as 1, "guarded" as 2, "moderate" as 3, "high" as 4, and "critical" as 5. Once all the questions have been answered, the client clicks "Run Assessment" and the tool processes the responses instantly, displaying a score out of 100 for each category described as low, medium, or high.

**Heat Map Visualization**

To the right of the category scores is the heat map, which provides a deeper visual breakdown of risk across the organization's systems. The heat map works by connecting each question to one or more of NLNB's critical systems such as FIN. As the client answers each question, that score is added to the total for every system that question affects. The tool then calculates an average score for each system, which gets converted into two values: likelihood and impact, both on a scale of 1 to 5. These two values are multiplied together and scaled to create a final score out of 100, which determines each system's rating as low, medium, high, or critical (80 and above). Each system is then placed into its corresponding cell on the heat map based on its impact and likelihood numbers. For example, if a user answers several FIN-related questions with high values, FIN's average rises, its impact and likelihood increase, and it moves into a hotter cell on the heat map, shifting its rating from Medium to High or Critical.

**Mitigation Recommendations**

Based on all of the scoring, the tool delivers custom mitigation recommendations at both the business and technical IT level, so decision-makers and IT staff both know exactly what steps to take next. Each of the 15 identified risks across NLNB's systems including FIN, BODPS, CMS, iReport, BeSecure, NorthGo, PeoplePay, and WeHelp receives two recommendations: one high-level business recommendation and one technical IT recommendation, aligning with NLNB's five-year implementation vision.

**Team GRQ**

This project was built by a five person consulting team as part of ETI 302 at Penn State University in Spring 2026, sponsored by EY. The team consisted of Tory Park as Project Leader, Kuan-en Lee as Developer and Support, Srinidhi Deekonda as Strategist and Facilitator, Tara Nguyen as Analyst and Quality Coordinator, and Daniel Simkanin as Research Lead.
