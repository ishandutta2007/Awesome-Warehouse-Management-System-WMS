# Awesome-Warehouse-Management-System-WMS

# Awesome Warehouse Management System (WMS)

> A curated list of top Warehouse Management System (WMS) platforms — both SaaS/Hosted commercial solutions and open-source alternatives for managing inventory, fulfillment, and warehouse operations.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Manhattan Active Warehouse Management](#manhattan-active-warehouse-management)
  - [Blue Yonder WMS](#blue-yonder-wms)
  - [Infor CloudSuite WMS](#infor-cloudsuite-wms)
  - [Körber (Infios Warehouse Edge)](#körber-infios-warehouse-edge)
  - [Zoho Inventory](#zoho-inventory)
  - [Oracle NetSuite WMS](#oracle-netsuite-wms)
  - [Fishbowl Warehouse](#fishbowl-warehouse)
  - [Logiwa IO](#logiwa-io)
  - [ShipHero](#shiphero)
  - [Deposco](#deposco)
- [Open-Source Software](#-open-source-software)
  - [GreaterWMS](#greaterwms)
  - [OpenBoxes](#openboxes)
  - [OpenWMS.org](#openwmsorg)
  - [myWMS](#mywms)
  - [OCA WMS (Odoo)](#oca-wms-odoo)
  - [frePPLe](#frepple)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Warehouse Management System platforms. These are not open-source but are included as reference points for feature comparison.

### Manhattan Active Warehouse Management
**Type:** Cloud-native enterprise WMS  
Manhattan Active WM is the industry's first cloud-native WMS, built entirely on microservices for effortless extensibility and continuous innovation [citation:4]. Named a Leader in the Gartner Magic Quadrant for WMS for the 18th consecutive time. The platform includes commercially released AI agents (January 2026) that autonomously analyze, decide, and execute workflows — warehouse-focused agents continuously monitor work queues, automation, and inventory to anticipate issues and optimize task orchestration, while a Labor Agent provides cross-department guidance on workforce deployment [citation:4]. Scales from mid-complexity warehouses to the world's largest distribution centers.  
**Best for:** Enterprises needing a proven, AI-augmented, cloud-native WMS that scales to the largest and most complex operations.

### Blue Yonder WMS
**Type:** Enterprise WMS with AI and pull-based streaming  
Blue Yonder's 2025.4 release introduced pull-based streaming that eliminates batches and turns orders into a continuous stream based on critical workflow needs, sequencing and releasing orders according to real-time capacity [citation:5]. Enhanced AI/ML capabilities include explainability, dynamic slotting, and work optimization. The Warehouse Ops Agent provides intraday task and labor forecasts with explanations, pre-shift briefs, resource swap recommendations, and dynamic slotting adjustments. Camera-based yard tracking automates trailer visibility, replacing manual audits [citation:5].  
**Best for:** Enterprises seeking AI-driven operational intelligence with capacity-aware, continuous order flow.

### Infor CloudSuite WMS
**Type:** Multi-owner, multi-facility enterprise WMS  
Infor CloudSuite WMS manages distribution center activities holistically for one location or dozens, combining warehouse fulfillment with embedded labor management and 3D visual analysis for a shorter learning curve [citation:12]. Features include appointment scheduling, directed put-away, returns, cross-docking, flow-through, voice/RF/e-commerce/kitting/allocation support, and customer-level costing, billing, and invoicing. Deployable on-premises or in the cloud [citation:12].  
**Best for:** 3PLs and multi-owner operations needing embedded labor management and 3D visualization with flexible deployment.

### Körber (Infios Warehouse Edge)
**Type:** End-to-end WMS with automation and voice  
Infios Warehouse Edge (formerly Körber K.Motion Warehouse Edge and HighJump WMS) provides full visibility into inventory, people, and processes with slotting/re-slotting algorithms, automatic consolidation, cross-docking, and real-time bin utilization [citation:6]. Integrates with AMRs and voice solutions for hands-free task guidance. Analytics and reporting include real-time KPI dashboards and drill-down charts. Integrates with major ERP, transportation, and yard management systems [citation:6].  
**Best for:** Operations wanting a proven WMS with strong automation integration (AMR, voice) and ERP connectivity.

### Zoho Inventory
**Type:** Cloud inventory and warehouse management for SMBs  
Zoho Inventory provides multi-warehouse management, bin-level stock organization, barcode scanning, picklists, and stock counts without halting operations [citation:3]. Real-time visibility across locations and sales channels, with built-in audit trails and approval workflows. Integrated with Zoho's broader ecosystem (Books, CRM) and supports Shopify, Amazon, and other channels.  
**Best for:** Small to mid-sized businesses wanting affordable, cloud-based warehouse inventory management with multi-channel support.

### Oracle NetSuite WMS
**Type:** WMS within NetSuite ERP  
NetSuite WMS provides warehouse management within the broader NetSuite ERP suite. The 2026v1 release includes enhancements for searching kit/package items, manual item receipt posting, reversal of inbound shipment receiving, zero quantity picks, and landed cost receiving . Suited for organizations already standardized on NetSuite for ERP and financials.  
**Best for:** NetSuite ERP customers wanting WMS functionality native to their existing platform.

### Fishbowl Warehouse
**Type:** SMB WMS with QuickBooks integration  
Fishbowl provides warehouse management for small and mid-size businesses with real-time inventory tracking, barcode scanning, pick/pack/ship, and multi-location support [citation:8]. The standout feature is seamless QuickBooks integration, keeping stock levels and financial records in sync automatically. Trusted by over 6,000 manufacturers, distributors, and product companies. Implementation takes 2–6 weeks with per-user pricing and no volume caps [citation:8].  
**Best for:** SMBs running QuickBooks needing a WMS layer with strong accounting integration and reasonable implementation timelines.

### Logiwa IO
**Type:** Cloud-native WMS for high-volume 3PL and DTC  
Logiwa IO is architected specifically for high-velocity, multi-tenant, parcel-driven ecommerce fulfillment [citation:9]. Features include native 3PL billing infrastructure (contract-governed multi-tenant billing, dimensional accuracy, VAS capture, automated margin management), AI-driven batching and path optimization (up to 25% pick throughput increase), algorithmic labor standards, and directed putaway logic. Deployment takes 4–6 weeks with no-code configuration for 90–95% of use cases [citation:9].  
**Best for:** 3PLs and high-volume DTC operations needing rapid deployment, native billing, and ecommerce-optimized fulfillment.

### ShipHero
**Type:** WMS for scaling 3PLs and DTC brands  
ShipHero provides real-time inventory tracking, automated putaway, mobile pick/pack with barcode scanning and smart routes, order management with returns and carrier rate shopping, and built-in reporting [citation:10]. Integrates with 150+ global carriers through Shiptheory for label automation. Barcode scanning accelerates workflows and verifies order accuracy at every step, reducing mis-picks and mis-shipments [citation:10].  
**Best for:** Growing 3PLs and DTC brands needing scalable, scanner-driven warehouse operations with strong carrier integrations.

### Deposco
**Type:** AI-powered WMS with MHE integrations  
Deposco's WMS includes Order Fulfillment Profiles for grouping, batching, and strategically allocating orders before pick wave release, plus advanced Directed Putaway intelligence that minimizes travel distances and optimizes space utilization [citation:11]. Pre-configured integrations with over a dozen MHE systems including ASRS, cobots, and AGVs (AutoStore, Locus Robotics). SCI solutions provide shipping optimization (up to 5% freight spend reduction) and root cause analysis [citation:11].  
**Best for:** Operations investing in warehouse automation (ASRS, AMRs) needing pre-built MHE integrations and AI-driven optimization.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Warehouse Management Systems. All listed projects offer source code you can deploy on your own infrastructure.

### GreaterWMS
**Stack:** Python / Django / Quasar (Vue.js) | **License:** Open Source (per repository)  
A highly customizable open-source WMS rebuilt with the Bomiot framework (Rust core) in version 3.0, featuring a plugin architecture and app marketplace [citation:13]. Designed for customization: frontend-backend separation (Django REST Framework + Quasar) enables independent evolution, modular business logic (ASN receiving, DN shipping, inventory, storage locations) allows modifying only needed modules, and the OneAPP concept serves PDAs, mobile apps, desktops, and websites from the same backend [citation:13]. Real-world deployments span 3PL/cloud warehouses, pharmaceutical distribution (inventory turnover days reduced from 45 to 28), cold-chain, cross-border e-commerce, and manufacturing (25% inventory turnover improvement).  
**Best for:** Organizations wanting a highly customizable open-source WMS foundation that can be adapted to 3PL, pharma, cold-chain, or manufacturing without vendor lock-in.

### OpenBoxes
**Stack:** (Check repository) | **License:** Open Source (per project)  
OpenBoxes is a warehouse management system designed to manage inventory and track stock movements specifically for healthcare facilities [citation:2]. 919 GitHub stars with active maintenance (updated weekly). Suited for hospitals, clinics, and public health supply chains needing traceability and stock visibility.  
**Best for:** Healthcare facilities and public health organizations needing inventory management tailored to medical supplies.

### OpenWMS.org
**Stack:** Java | **License:** Open Source (per project)  
A reference open-source WMS implementation with 754 GitHub stars, updated recently [citation:2]. Focuses on core warehouse processes with a modular approach. While not as actively developed as larger ERP-anchored projects, it remains a reference implementation for basic WMS concepts. Modern integrations often require custom adapters [citation:14].  
**Best for:** Learning, proofs of concept, or small sites with simple, stable processes and tolerance for DIY integrations.

### myWMS
**Stack:** Java | **License:** Open Source (per project)  
A classic open-source WMS with 131 GitHub stars, updated recently [citation:2]. Focused on core warehouse management functionality. A branch (salimvanak/mywms) also exists. Suited for small to mid-sized operations needing a straightforward Java-based WMS.  
**Best for:** Java-centric teams wanting a simple, self-hosted WMS foundation.

### OCA WMS (Odoo)
**Stack:** Python (Odoo) | **License:** AGPL-3.0 (Odoo Community)  
The Odoo Community Association's WMS modules extend Odoo's inventory capabilities with advanced logistic features [citation:2]. 226 GitHub stars, updated recently. Leverages Odoo's broader ERP ecosystem while adding warehouse-specific functionality.  
**Best for:** Organizations already using Odoo Community needing advanced WMS capabilities within the same platform.

### frePPLe
**Stack:** Python / PostgreSQL | **License:** Open Source (per project)  
An open-source supply chain planning platform with 771 GitHub stars, updated recently [citation:2]. While not a pure WMS, it provides production planning, distribution planning, and inventory optimization that complements warehouse execution.  
**Best for:** Organizations needing supply chain planning (demand, inventory, production) alongside or upstream of warehouse execution.

---

## 📊 Comparison at a Glance

| Software | License | Type | Deployment | Best For |
|----------|---------|------|------------|----------|
| **Manhattan Active WM** | Proprietary | Cloud-native enterprise | SaaS | Largest, most complex DCs |
| **Blue Yonder WMS** | Proprietary | Enterprise + AI | SaaS | AI-driven continuous flow |
| **Infor CloudSuite WMS** | Proprietary | Multi-owner enterprise | SaaS/on-prem | 3PLs + labor management |
| **Körber Infios** | Proprietary | Automation + voice | SaaS/on-prem | AMR/voice integration |
| **Zoho Inventory** | Proprietary | SMB cloud WMS | SaaS | Affordable multi-channel |
| **NetSuite WMS** | Proprietary | ERP-integrated | SaaS | NetSuite ERP customers |
| **Fishbowl** | Proprietary | SMB + QuickBooks | SaaS/on-prem | QuickBooks users |
| **Logiwa IO** | Proprietary | 3PL/DTC cloud WMS | SaaS | Rapid 3PL deployment |
| **ShipHero** | Proprietary | 3PL/DTC WMS | SaaS | Scanner-driven fulfillment |
| **Deposco** | Proprietary | AI + MHE WMS | SaaS | Automation-heavy operations |
| **GreaterWMS** | Open Source | Customizable OSS WMS | Self-hosted | Deep customization + no lock-in |
| **OpenBoxes** | Open Source | Healthcare WMS | Self-hosted | Hospitals + public health |
| **OpenWMS.org** | Open Source | Reference OSS WMS | Self-hosted | Learning / simple sites |
| **myWMS** | Open Source | Java OSS WMS | Self-hosted | Simple Java-based WMS |
| **OCA WMS (Odoo)** | AGPL-3.0 | Odoo WMS modules | Self-hosted | Odoo Community users |
| **frePPLe** | Open Source | Supply chain planning | Self-hosted | Planning upstream of WMS |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Warehouse Management System (WMS) that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source WMS ecosystem is more limited than for some other categories; many production-grade options are ERP modules (Odoo, ERPNext) rather than standalone WMS platforms.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
