# expa_automator_mk1
Project done as part of my work as <i>Outgoing Exchange Manager</i> for <i>AIESEC in NUS</i>

This project aims to reduce workload of my Outgoing Exchange team through eliminating the need for manual data entry. Previously, this was done by manually checking our global CRM / information system (nicknamed EXPA) for information on our customers (commonly referred to as exchange participants or EPs), and entering the related numbers in a spreadsheet for performance tracking.

Firstly, <b>"expa_leads.ipynb"</b> processes and cleans the data, obtained from the EXPA API and structured in NoSQL (<b>"2018_ep_demo.txt"</b>) - keeping only the fields relevant to our daily processes. Then, <b>"expa_analytics.ipynb"</b> performs descriptive analytics and data visualization, providing customer insights e.g. referral source, sign-ups by month, product interest, etc, which the executive board of AIESEC in NUS can then refer to when making marketing-related decisions.

Notes:
- AIESEC in NUS has two Outgoing Exchange departments handling two different products (then named OGV and OGT), hence data is segregated for the convenience of both departments.
- As EXPA data is restricted to AIESEC members only, <b>"2018_ep_demo.txt"</b> only contains one fictional customer (but with information conveyed in the same schema) for demonstration purposes.

I subsequently improved on this project using R to automatically scrape and process data from EXPA API, you may refer to it [here](https://github.com/kaiwei-tan/expa_automator_mk2/).
