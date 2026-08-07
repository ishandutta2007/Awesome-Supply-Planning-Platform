# Awesome-Supply-Planning-Platform

## Top Supply Planning Platform Tools Ecosystem

**Curated List of SaaS/Commercial Products & Open-Source GitHub Projects**  
*Focused on Advanced Planning & Scheduling (APS), Demand & Supply Planning, S&OP/IBP, Inventory Optimization & Production Scheduling*  
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Supply Planning**. These tools help manufacturers and supply chain teams balance demand and supply, optimize inventory, schedule production against constraints, run what-if scenarios, and support Sales & Operations Planning (S&OP) or Integrated Business Planning (IBP) processes.

**Examples** include Kinaxis RapidResponse, RELEX Solutions, Blue Yonder Supply Planning, ToolsGroup, Anaplan, OMP Unison Planning, PlanetTogether, Arkieva, John Galt Solutions, and Logility (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted APS, MRP, production scheduling, and supply chain planning — ideal for manufacturers and teams that want constraint-based planning without enterprise licensing costs.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Kinaxis RapidResponse](https://www.kinaxis.com/)**  
  Concurrent planning platform known for fast what-if scenario analysis across demand, supply, inventory, and capacity in a single environment.

- **[RELEX Solutions](https://www.relexsolutions.com/)**  
  Retail- and CPG-focused supply chain planning platform strong in demand forecasting, inventory optimization, and fresh/perishable management.

- **[Blue Yonder Supply Planning](https://blueyonder.com/)**  
  Enterprise supply chain planning suite covering demand, supply, inventory, and related execution capabilities within the broader Luminate platform.

- **[ToolsGroup](https://www.toolsgroup.com/)**  
  Specialized demand and inventory planning solutions emphasizing probabilistic forecasting and multi-echelon inventory optimization.

- **[Anaplan](https://www.anaplan.com/)**  
  Flexible connected-planning platform widely used for S&OP, financial planning, and supply chain scenario modeling.

- **[OMP Unison Planning](https://omp.com/)**, **[PlanetTogether](https://www.planettogether.com/)**, **[Arkieva](https://arkieva.com/)**, **[John Galt Solutions](https://johngalt.com/)**, **[Logility](https://www.logility.com/)**  
  Additional strong platforms offering advanced planning, finite scheduling, demand planning, and integrated supply chain decision support.

## Open-Source GitHub Projects

- **[frePPLe](https://github.com/frePPLe/frepple)**  
  Leading open-source supply chain planning and APS tool. Provides demand forecasting, constraint-based production planning and scheduling (theory of constraints, pull-based, lean principles), and integration capabilities for manufacturing companies.

- **[ERPNext](https://github.com/frappe/erpnext)**  
  Fully open-source ERP with strong manufacturing and MRP modules, including multi-level BOMs, production planning, work orders, material requirements, and capacity-related features.

- **[Odoo Community (Manufacturing / MRP)](https://github.com/odoo/odoo)**  
  Modular open-source ERP whose manufacturing apps support BOMs, work orders, basic MRP, quality, and maintenance — frequently used as a foundation for production planning.

- **[Timefold Solver](https://github.com/TimefoldAI/timefold-solver)** (successor to OptaPlanner)  
  Open-source constraint solver and planning engine excellent for building custom finite scheduling, resource allocation, and optimization applications.

- **[Google OR-Tools](https://github.com/google/or-tools)**  
  Powerful open-source optimization library (CP-SAT, linear/mixed-integer programming, routing) widely used to build custom supply and production planning solvers.

- **[python-lekin and similar APS libraries](https://github.com/)**  
  Emerging open-source flexible job-shop and supply chain scheduling libraries useful for research, prototyping, and custom APS development.

- **[IBM CMMPPT / related constrained planning tools](https://github.com/IBM/CMMPPT)**  
  Open-source constrained materials management and production planning components for optimal resource allocation against BOMs and capacity.

- **[Specialized logistics & health supply chain systems](https://github.com/msupply-foundation/open-msupply)**  
  Domain-focused open-source logistics management information systems (e.g., open mSupply) that address planning and distribution in specific verticals.

### Additional Strong Open-Source Options

- Custom planning models built with PuLP, Pyomo, or other Python optimization stacks.
- Integration of forecasting libraries (Prophet, statsmodels, etc.) with ERPNext/Odoo or frePPLe.
- Research and academic APS/scheduling prototypes available on GitHub.
- Spreadsheet-to-optimizer workflows and lightweight scenario engines for smaller operations.

**Frameworks for building custom systems**: Start with **frePPLe** for a ready-to-run open-source APS experience. Use **ERPNext** or **Odoo** when you need planning tightly integrated with broader ERP processes. For advanced or highly customized finite scheduling, combine **Timefold** or **OR-Tools** with your own data model and UI. Layer forecasting and inventory optimization logic on top of these foundations.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/commercial or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Supply planning at enterprise scale involves complex constraints, multi-echelon networks, and high data quality requirements. Open-source tools (especially frePPLe and ERP/MRP modules) are capable for many manufacturing use cases but may require more configuration, integration, and algorithmic tuning than mature commercial APS platforms.
- Always validate planning results against business rules, capacity realities, and financial impact before operational use.

---

**Made for supply chain planners, manufacturing engineers, and teams seeking open, constraint-based planning capabilities.**  
Let's make advanced planning more accessible and transparent.
