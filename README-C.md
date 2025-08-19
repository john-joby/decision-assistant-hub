<style>
  body {
    font-family: "IBM Plex Sans", sans-serif;
  }
  h1 img, h2 img, h3 img {
    vertical-align: middle;
    margin-right: 6px;
  }
</style>

# <img src="https://carbondesignsystem.com/assets/icons/ai-status-complete.svg" width="26"/> Decision Assistant Hub

The **Decision Assistant Hub** is the companion repository to the [Decision Assistant](#), an AI-powered assistant that helps users turn business policies into structured decision models like rulesets and DMN diagrams.

This hub provides **curated examples**, **tutorials**, **tips**, and **video walkthroughs** to help you understand how to work with the assistant and apply it to real-world decision automation scenarios.

---

## <img src="https://carbondesignsystem.com/assets/icons/bullseye.svg" width="22"/> Purpose

This repository is for:
- <img src="https://carbondesignsystem.com/assets/icons/book.svg" width="18"/> Learning how to convert natural language policies into formalized decision models  
- <img src="https://carbondesignsystem.com/assets/icons/beaker.svg" width="18"/> Exploring domain-specific examples with rule outputs  
- <img src="https://carbondesignsystem.com/assets/icons/video.svg" width="18"/> Watching guided walkthroughs and demos  
- <img src="https://carbondesignsystem.com/assets/icons/lightbulb.svg" width="18"/> Getting tips, prompt ideas, and modeling strategies  

---

## <img src="https://carbondesignsystem.com/assets/icons/folder.svg" width="22"/> Repository Structure

| Folder | Description |
|--------|-------------|
| `examples/` | Sample business policies and their automated decision models, organized by domain |
| `docs/` | Getting started guides, tips, and FAQs |
| `media/` | Screenshots and video walkthroughs |
| `tutorials/` | Step-by-step usage guides |
| `CONTRIBUTING.md` | Guidelines for contributing new examples or content |

---

## <img src="https://carbondesignsystem.com/assets/icons/book.svg" width="22"/> Example Use Cases by Domain

### <img src="https://carbondesignsystem.com/assets/icons/user-multiple.svg" width="20"/> HR
- **[Time Off](examples/hr/time_off_policy/)** – Automate leave types, accruals, eligibility, and carryover logic.  
- **[Performance Bonus](examples/hr/performance_bonus_policy/)** – Rules to determine bonus eligibility based on performance tiers and seniority.  

### <img src="https://carbondesignsystem.com/assets/icons/currency-dollar.svg" width="20"/> Finance
- **[Expense Approval](examples/finance/expense_approval/)** – Multi-level approval rules and threshold-based routing using a decision table.  

### <img src="https://carbondesignsystem.com/assets/icons/shield-check.svg" width="20"/> Compliance
- **[Anti-Money Laundering (AML)](examples/compliance/aml_policy/)** – Transaction pattern rules and risk classification logic.  
- **[Know Your Customer (KYC)](examples/compliance/kyc_policy/)** – Decision logic for onboarding, document verification, and customer risk scoring.  

### <img src="https://carbondesignsystem.com/assets/icons/industry.svg" width="20"/> Operations
- **[Vendor Risk Scoring](examples/operations/vendor_risk_scoring/)** – Model for supplier assessment using weighted risk attributes and thresholds.  

---

## <img src="https://carbondesignsystem.com/assets/icons/launch.svg" width="22"/> Get Started

1. <img src="https://carbondesignsystem.com/assets/icons/tool-kit.svg" width="18"/> Make sure you're set up with the **Decision Assistant**  
2. <img src="https://carbondesignsystem.com/assets/icons/folder.svg" width="18"/> Browse the `examples/` folder by domain to find a scenario similar to yours.  
3. <img src="https://carbondesignsystem.com/assets/icons/ai-status.svg" width="18"/> Read the `policy.md`, then explore the generated rules (`rules.md`, `.json`, or `.dmn`).  
4. <img src="https://carbondesignsystem.com/assets/icons/video.svg" width="18"/> Watch demo videos in [`media/videos/`](media/videos/).  

---

## <img src="https://carbondesignsystem.com/assets/icons/lightbulb.svg" width="22"/> [Practical Guide to Writing Policies](docs/tips_and_tricks.md)

---

## <img src="https://carbondesignsystem.com/assets/icons/help.svg" width="22"/> FAQ

**Q:** What formats are supported for policies?  
**A:** Currently: Raw text in the assistant.  

Full FAQ: [`docs/faq.md`](docs/faq.md)

---

## <img src="https://carbondesignsystem.com/assets/icons/collaborate.svg" width="22"/> Contributing

We welcome contributions!  
[`Click Here`](CONTRIBUTING.md) for guidelines.

---

## <img src="https://carbondesignsystem.com/assets/icons/license-draft.svg" width="22"/> License

This project is licensed under the **Apache 2.0**.
