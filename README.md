# SEC-FinRep-Analysis
 A fairly simple program to evaluate 10K financial reports. Does not support downloads, only operations on user organized 10-K reports :P.


**Specification**:
  - Given set of 10-K .xlsx financial reports\* for a given company, read into dataframes for easier analyis, and generate visualizations for trend analysis.

  - Supported Analytics:
    - Vertical & Horizontal Analysis
    - Common Ratio Analysis
      - Du Pont Model (Margin & Turnover)
      - ROI
      - ROE
      - Working Capital
      - Current Ratio
      - Acid Test Ratio

  **WARNING** : Currently reliant on local organization of excel files - I don't care where you put the folder but for successful use:
        - Put all financial reports in a single folder solely for the .xlsx files
        - *STANDARDIZE* names in this form:
            - For a given fiscal year** \<YEAR\> and company \<NAME\>, the financial report should be renamed:
                  - "FY\<YEAR\>\_\<NAME\>\_Report.xlsx"


**Motivation** :
  - Save me some time on my accounting class project by automating ratio analysis (and flex just a little bit)
  - Do the above, but in such way that I've built a relatively efficient and extensible
  API to assist me as a I invest more and more intelligently (although fundamentals are dead???)
