![enter image description here](https://7964e189fb9a08f4a51c194383012c8d.cdn.bubble.io/f1761771685531x347390430785958500/godelcloud.banner.png  )

# List of FCA Authorised & Registered UK AIFMs | Data Dictionary
**Dataset:** [UK Alternative Investment Fund Managers](https://godelcloud.com/uk-aifm-dataset) [by GodelCloud | Q4 2025]

This table provides a reference for the data fields included in GodelCloud’s Dataset of UK AIFMs, listing each variable with its data type and description.


---

| <span align='left'>**Field Name**</span> | **Data Type** | **Description** |
|----------------|---------------|-----------------|
| **Firm Details** |  |  |
| frn | int | FCA Firm Reference Number (e.g. 123467) |
| name | str | Firm’s legal name (e.g. ABC Ltd) |
| class | str | AIFM classification (Full-Scope, Small Authorised, Small Registered) |
| aif_permission | str | Type of fund(s) authorised to manage (Managing an authorised AIF, Managing an unauthorised AIF, Both) |
| status_aifm | str | Authorisation status under AIFMD (Authorised, Registered) |
| status_firm | str | Authorisation status under FCA (e.g. Authorised, Authorised – applied to cancel) |
| status_effective_date | date | Date the firm’s current FCA authorisation status became effective |
| firm_type | str | Firm's regulated type (e.g. Regulated) |
| principal | boolean | Indicates if the firm is a principal under the Appointed Representative regime (True = Principal, False = Not Principal) |
| appointed_rep_count | int | Number of appointed representatives managed by the firm |
| small_reg_cat | str | Registration category of small registered AIFMs (EuVECA, Property AIFM, Internally Managed AIFM) |
| employee_size | str | Employee size band based on firm’s public LinkedIn data (e.g. 1–10, 11–50, 51–200) |
| website | str | Firm’s corporate website URL |
| domain | str | Domain of the website (e.g. example.com) |
| linkedin | str | Firm's LinkedIn company URL |
| **Investment Permissions** |  |  |
| managing_authorised_aif | boolean | Managing an authorised AIF |
| managing_unauthorised_aif | boolean | Managing an unauthorised AIF |
| advising_on_investments | boolean | Advising on investments (excluding Pension Transfers and Pension Opt Outs) |
| arranging_investments | boolean | Arranging (bringing about) deals in investments |
| dealing_as_agent | boolean | Dealing in investments as agent |
| dealing_as_principal | boolean | Dealing in investments as principal |
| establish_operate_wind_cis | boolean | Establishing, operating or winding up a collective investment scheme |
| making_arrangements | boolean | Making arrangements with a view to transactions in investments |
| managing_investments | boolean | Managing investments |
| p2p_advising | boolean | Advising on P2P agreements |
| safeguarding | boolean | Arranging safeguarding and administration of assets |
| safeguarding_without_arranging | boolean | Safeguarding and administration of assets (without arranging) |
| ucits | boolean | Managing a UK UCITS |
| mifid_client_types | str | MiFID client categories served (Eligible Counterparty, Professional, Retail) |
| s21_approver | boolean | Indicates if the firm can approve financial promotions for unauthorised persons |
| s21_investment_types | str | Investment types a Section 21 approver may approve (Units, Warrants, Debentures) |
| **Senior Management Function (SMF) Counts** |  |  |
| cf_headcount | int | Count of unique individuals holding certified or senior management functions |
| smf_headcount | int | Count of unique individuals holding Senior Management Functions (SMFs) |
| smf17_mlro | int | SMF17 – Money Laundering Reporting Officer |
| smf16_compliance_oversight | int | SMF16 – Compliance Oversight |
| smf1_chief_executive | int | SMF1 – Chief Executive |
| smf3_executive_director | int | SMF3 – Executive Director |
| smf27_partner | int | SMF27 – Partner |
| smf9_chair_governing_body | int | SMF9 – Chair of the Governing Body |
| smf2_chief_finance | int | SMF2 – Chief Finance |
| smf24_chief_operations | int | SMF24 – Chief Operations |
| smf4_chief_risk | int | SMF4 – Chief Risk |
| smf18_other_overall | int | SMF18 – Other Overall Responsibility |
| smf5_head_internal_audit | int | SMF5 – Head of Internal Audit |
| smf7_group_entity_senior_mgr | int | SMF7 – Group Entity Senior Manager |
| smf12_chair_remuneration_comm | int | SMF12 – Chair of the Remuneration Committee |
| smf10_chair_risk_comm | int | SMF10 – Chair of the Risk Committee |
| smf11_chair_audit_comm | int | SMF11 – Chair of the Audit Committee |
| smf13_chair_nominations_comm | int | SMF13 – Chair of the Nominations Committee |
| smf14_senior_independent_director | int | SMF14 – Senior Independent Director |
| smf19_head_overseas | int | SMF19 – Head of Overseas Branch / Head of Overseas |
| **Company Registration** |  |  |
| chn | str | Companies House Number |
| ch_name | str | Companies House Name |
| ch_status | str | Companies House Status (e.g. Active, Liquidation) |
| ch_type | str | Companies House Legal Form (e.g. LTD, LLP) |
| date_of_creation | date | Companies House Incorporation Date |
| sic_codes | str | Standard Industrial Classification (SIC) codes (e.g. 64999) |
| **Balance Sheet and P&L (Companies House)** |  |  |
| turnover | int | Reported turnover in GBP |
| cash_in_bank | int | Reported cash in bank in GBP |
| total_assets | int | Reported total assets in GBP (e.g. 1 500 000) |
| total_liabilities | int | Reported total liabilities in GBP (e.g. 900 000) |
| net_assets | int | Reported net assets in GBP |
| debt_ratio | float | Debt ratio = (total liabilities ÷ total assets × 100) (e.g. 60) |
| accounts_year_ended | str | Financial year-end date (e.g. 31 Mar 2025) |
| **Physical Address** |  |  |
| address_line_1 | str | Primary address line |
| address_line_2 | str | Secondary address line (if applicable) |
| address_line_3 | str | Additional address line (if applicable) |
| postcode | str | UK postcode |
| area | str | Local area or district (e.g. City of London) |
| region | str | UK region (e.g. London) |
| country | str | Country of registration (United Kingdom) |

---

**Source:** [GodelCloud's Dataset of UK AIFMs](https://godelcloud.com/uk-aifm-dataset) | Q4 2025

<hr>

© 2025 GodelCloud
