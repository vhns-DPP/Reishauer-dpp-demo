# REISHAUER Digital Product Passport (DPP) Demonstrator

## Overview

This repository contains a demonstrator implementation of a Digital Product Passport (DPP) and Asset Administration Shell (AAS) for a REISHAUER clamping device (Spannmittel DH 28).

The demonstrator has been developed within a pilot project between REISHAUER AG and the Competence Center for Automation & Digitalisation to explore how product-related information can be structured, linked and presented using modern Digital Product Passport concepts.

The current demonstrator combines:

- Asset Administration Shell (AAS)
- Digital Product Passport (DPP)
- Product documentation
- Technical specifications
- Bill of Materials (BOM)
- Material information
- Lifecycle and repair information
- Illustrative sustainability information
- Mobile and web-based user interfaces

---

# Live Demonstrator

https://vhns-dpp.github.io/Reishauer-dpp-demo/

---

# Repository Structure

```text
/
│
├── index.html
│   Main DPP web application
│
├── README.md
│   Repository documentation
│
├── aasx/
│   Asset Administration Shell packages
│
│   ├── Reishauer_Spannmittel_DH28_DPP_V2_valid.aasx
│   └── Reishauer_Spannmittel_DH28_DPP_V2_2_CO2_valid.aasx
│
├── docs/
│   Product-related documentation
│
│   ├── Bedienungsanleitung_DH.pdf
│   ├── Reparaturblatt_Spannmittel.pdf
│   ├── Kundenzeichnung_42712700_SKD.pdf
│   ├── Aufspannzeichnung_42600919_SKD.pdf
│   └── Stueckliste_42712700.xlsx
│
└── assets/
    Images used by the DPP

    ├── Spannmittel.png
    ├── Anlagering.png
    ├── Zwischenbuchse.png
    ├── Kontrollring.png
    └── OEM_Label.png
```

---

# Demonstrated DPP Capabilities

## Product Identity

The demonstrator provides:

- Product identification
- Material number
- Serial number
- Manufacturer information
- QR-code based access
- Digital product representation

---

## Technical Information

The DPP integrates key technical information such as:

- Operating pressure
- Maximum rotational speed
- Machine compatibility
- Assembly information
- Product configuration data

---

## Documentation Integration

The DPP links directly to relevant product documentation:

- Operating manuals
- Repair documentation
- Technical drawings
- Assembly drawings
- Bill of Materials (BOM)

This allows users to access all relevant information from a single digital entry point.

---

# Material Intelligence

The demonstrator enriches the traditional Bill of Materials with additional material-related information.

Current capabilities include:

- Material classification
- Material distribution
- Material composition
- Chemical composition of selected materials

Examples:

- 1.6587 (18CrNiMo7-6)
- 1.1191 (C45E)
- 1.3343 (HS6-5-2C)

The objective is to demonstrate how future Digital Product Passports may support transparency regarding product composition and circularity.

---

# Lifecycle Information

The demonstrator includes lifecycle-related information such as:

- Guaranteed lifetime
- Repairability information
- Service information
- Reconditioning potential

Example:

- Guaranteed lifetime: 105'000 clamping cycles
- Repair options: Partial repair or complete overhaul
- Expected lifetime: 10+ years with regular maintenance and refurbishment

---

# Sustainability Demonstrator

The repository contains an illustrative sustainability demonstrator.

Current visualisations include:

- Material distribution
- Supplier contribution
- Illustrative CO₂ contribution

## Important Notice

The CO₂ values shown in the demonstrator are illustrative demonstration values only.

They are NOT:

- Product Carbon Footprints (PCF)
- Corporate Carbon Footprints
- Validated sustainability data
- Verified environmental declarations

The values are solely intended to demonstrate how sustainability-related information could be integrated into future Digital Product Passports.

---

# Asset Administration Shell (AAS)

The repository contains Asset Administration Shell packages compatible with the IDTA Asset Administration Shell concept.

Current versions:

| File | Description |
|--------|--------|
| Reishauer_Spannmittel_DH28_DPP_V2_valid.aasx | Base demonstrator |
| Reishauer_Spannmittel_DH28_DPP_V2_2_CO2_valid.aasx | Extended demonstrator including material and sustainability submodels |

---

# Viewing the AAS

The AAS packages can be opened with:

- Eclipse AASX Package Explorer
- Eclipse BaSyx
- IDTA-compatible AAS environments
- Other Asset Administration Shell tools

---

# Current Maturity Level

## Demonstrator / Pilot Stage

Implemented:

- Product structure
- Documentation integration
- Asset Administration Shell
- Mobile DPP interface
- Material dashboard
- Sustainability demonstrator

Potential future extensions:

- Supplier integration
- Validated Product Carbon Footprints
- DPP compliance extensions
- Data Space integration
- Service history
- Repair history
- Lifecycle event tracking
- Circularity indicators
- Automated sustainability reporting

---

# Access Control Demonstrator

The current web demonstrator includes a simple example of protected DPP information areas.

In this version, selected extended product information is no longer displayed publicly. Instead, the user first sees a protected information area and must enter a password before the following content is shown:

- Stückliste
- Supplier Information
- Extended Material Data
- Material Composition
- Sustainability Demonstrator
- Illustrative CO₂ Demonstrator

Demo password:

```text
XXXXXXXXXXXXXXXX
```

## Important Security Notice

This password mechanism is for demonstration purposes only.

It is intended to illustrate the concept that not all DPP/AAS information must be publicly accessible. It is not a secure authentication or authorization mechanism.

For a productive implementation, access control should be implemented using proper mechanisms such as:

- private repositories or protected hosting
- user authentication
- role-based access control
- secure AAS server infrastructure
- identity and access management
- Data Space compatible access policies

---

# Project Context

This demonstrator was developed as part of an exploratory pilot project to evaluate how Digital Product Passports and Asset Administration Shells can support future product transparency, lifecycle management, service processes and sustainability reporting.

The implementation should be regarded as a proof-of-concept and discussion platform for future developments.

---

# Contact

**Competence Center for Automation & Digitalisation**

Digital Product Passport Demonstrator for REISHAUER AG
