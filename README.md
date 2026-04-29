**READ ME**

**The Paris Club Dataset (1956–2026):**   
**Sovereign Debt Restructuring Agreements**

## **1\. Dataset Contents and Coverage**

This dataset provides comprehensive structured data on all 543 sovereign debt restructuring agreements negotiated through the Paris Club from its first meeting on 16 May 1956 through 14 April 2026, covering 102 debtor countries and US$863 billion in treated debt. The Paris Club is an informal group of official creditor countries that coordinates debt restructurings for debtor nations facing payment difficulties.

Published in April 2026, the dataset enables analysis impossible before without extensive data engineering: comprehensive creditor and debtor mapping over 70 years of debt restructuring agreements, as well as metadata at the agreement level on meeting chairs, debtor delegations, observing parties, associated documentation, and more. Key variables on the agreement level are shown below, and a comprehensive list of metadata is provided in the dataset excel file:

* **Debtor country and participating creditor countries**

* **Amounts treated** (total, cancelled, and rescheduled)

* **Treatment terms** (Naples terms, HIPC Initiative Exit terms, Evian terms, etc.)

* **Categories of debt treated** and repayment profiles

* **Cut-off dates** for eligible debt

* **Meeting chair and head of debtor delegation**

* **Observer organizations** present at signing

* **Specific provisions** and comparability of treatment clauses

* **Total external debt** of the debtor country

* **Links to supporting documentation** (press releases, IMF agreements, Agreed Minutes) 

In terms of terminology, we take “agreement” to refer to the formal documented deal between the Paris Club and a debtor country, recorded in the “Agreed Minutes” signed by all participating creditors. “Treatment” denotes the specific terms and conditions applied within that agreement, which define the type and generosity of debt relief offered. “Restructuring” is the umbrella term encompassing any modification of debt obligations to reduce or postpone repayment, including changes to maturity schedules, interest rates, grace periods, or nominal debt reduction. “Rescheduling” is a specific type of restructuring that extends the repayment timeline of debt without necessarily reducing its face value—a maturity extension mechanism that, while part of most Paris Club agreements, is distinct from debt cancellation or forgiveness. Virtually all Paris Club agreements into the second half of the 1980s involved a rescheduling of the debt only.

## **2\. File Formats and Structure**

The [dataset](https://doi.org/10.7910/DVN/BBWLO8) is provided in four formats to accommodate different research needs:

* **Excel workbook** – The complete dataset, which includes both long and tabular layouts for flexible analysis, and notes on individual fields where manual editing was required.

* **CSV long format** – Optimized for machine reading. Note that individual cell notes (of manual edits) are not inherited from the excel file.

* **CSV tabular format** – Optimized for human reading and browsing. Note that individual cell notes (of manual edits) are not inherited from the excel file.  
    
* **CSV network format** – Optimized for network analysis of creditors, debtors, and observers. Note that individual cell notes (of manual edits) are not inherited from the excel file.

All monetary values have been converted from text strings to numeric format, with extensive validation to address inconsistencies in the source data.

**3\. Intended Use Cases**

This resource addresses a significant gap in publicly accessible international finance data, and supports multiple research applications:

- Long-term trend analysis of Paris Club activity across seven decades  

- Creditor participation patterns (which countries participate most frequently and under what circumstances )

- Debtor return frequency, identifying countries that return to the Club multiple times  

- Comparative sovereign debt restructuring research, analyzing differences in treatment by debtor characteristics, time period, or creditor composition  

- Transparency and accountability research, examining the Paris Club’s operations and decision-making patterns  

- More granular and qualitative research on individual debt restructuring cases, where national reporting may not be available

- Combination with other datasets 

## **4\. Key Limitations**

See Methodology.pdf Section 5 for full discussion of known limitations and challenges. Some key limitations of the dataset include:

- *Website updates* \- The method for constructing this dataset relies on web scraping methods that are vulnerable to structural changes on the Paris Club website. Website updates (such as one encountered between February and October 2025\) would involve updating the scraping methodology, or adding new data (such as newly published agreements or broken URLs) by hand.

- *Missing values and data availability* \- The Paris Club has not published information consistently across all agreements or time periods. Missing values occur for several reasons, including limited available metadata, website inconsistencies, or agreement-specific variations.  
    
- *Data Quality issues* \- These include URL integrity, inconsistent formatting, country name variations, and creditor name changes.

## **5\. Citation**

Preferred citation:

Van der Zaag, Jochem Date; Van Mourik, Sven; Blackmon, Pamela, 2026, “The Paris Club Dataset (1956–2026): Sovereign Debt Restructuring Agreements”, Harvard Dataverse, V1, [https://doi.org/10.7910/DVN/BBWLO8](https://doi.org/10.7910/DVN/BBWLO8) 

All data and documentation are licensed under Creative Commons Attribution 4.0 International (CC BY 4.0), permitting reuse with attribution.

The Python code used for web scraping and data processing is hosted under the GPL-3.0 license at: [https://github.com/grimelda/openparisclub](https://github.com/grimelda/openparisclub) 

## **6\. Contact**

Date van der Zaag \- [altitudezero@proton.me](mailto:altitudezero@proton.me)

## **7\. More Information**

See Methodology.pdf for:

- Complete data collection procedures  
- Variable definitions and metadata/codebook (Section 4.2)  
- Known limitations and challenges

## **8\. Last Updated**

LAST UPDATED: April 2026

VERSION: 1.0
