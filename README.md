# Market Entry Packs (MEPs) – Technical Repository

## Overview

This repository contains the complete source code, assets, documentation, and deployment resources for all Market Entry Packs (MEPs) developed under the programme.

The repository has been created to support long-term ownership, maintenance, and sustainability by ensuring that programme teams, funders, and technical partners can:

- Access all Market Entry Packs in one location
- Edit and update content independently
- Understand the technical architecture and deployment process
- Host packs permanently on the funder's website or preferred hosting platform
- Troubleshoot, maintain, and enhance packs after handover

Each Market Entry Pack follows a standardised build structure while containing country-specific content.

---

## Included Market Entry Packs

- 🇬🇭 Ghana
- 🇰🇪 Kenya
- 🇷🇼 Rwanda
- 🇳🇬 Nigeria
- 🇨🇩 Democratic Republic of Congo (DRC)
- 🇿🇦 South Africa
- 🇺🇬 Uganda

> **Note:** The Nigeria and DRC packs are currently undergoing final debugging and quality assurance checks.

---

## Technology Stack

All Market Entry Packs are built using:

- HTML5
- CSS3
- Vanilla JavaScript
- Supabase (database, authentication, and content management)
- Google Fonts (DM Sans)

The packs are designed as static web applications and can be deployed on a wide range of hosting platforms.

---

## Repository Structure

```text
.
├── README.md
├── docs/
│   ├── handover-documentation.docx
│   ├── deployment-guide.md
│   └── troubleshooting-guide.md
│
├── shared-assets/
│   ├── images/
│   ├── icons/
│   └── branding/
│
├── templates/
│   └── base-mep-template/
│
└── market-entry-packs/
    ├── ghana/
    ├── kenya/
    ├── rwanda/
    ├── nigeria/
    ├── drc/
    ├── south-africa/
    └── uganda/
