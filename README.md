# Awesome-Battery-Energy-Storage-Management

# Top Battery Energy Storage Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Battery Analytics, BESS Optimization & Energy Storage Operations*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Battery Energy Storage Management**. These tools monitor, analyze, and optimize battery performance, state of health (SoH), degradation, and operational efficiency for grid-scale BESS, electric vehicles, and renewable energy integration.

**Examples** include TWAICE, ACCURE Battery Intelligence, Breathe Battery Technologies, BatterMachine, Voltaiq, About:Energy, Battery Cloud, PowerUp, Brill Power, BMS PowerSafe, Stem, Ampcontrol, Fluence Mosaic, Banyan Infrastructure, Nuvation Energy, Yotta Energy, Enode, and Piclo Flex (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom BMS development, and transparent battery analytics — ideal for researchers, energy storage developers, and engineers building vendor-independent battery management solutions. The open-source ecosystem for battery management is notably strong, with production-grade BMS platforms, optimization frameworks, and degradation models available.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[TWAICE](https://www.twaice.com/)**
  Analytics platform built for real-world battery energy storage operations at scale. Uses predictive analytics to anticipate degradation, optimize performance, and extend lifetime. Helped deliver average +5% improvement in recoverable energy and reduce analyst time per asset by 80-90%. Secured €24 million from European Investment Bank in 2026 .

- **[ACCURE Battery Intelligence](https://www.accure.net/)**
  Assurance and outperformance layer for grid-scale battery assets supporting 24+ GWh of operational BESS capacity. Combines AI with physics-based battery models for cell-level diagnostics, warranty intelligence, and PCS analytics. Won 2024 Energy Storage Award for Safety Product of the Year .

- **[Breathe Battery Technologies](https://www.breathebattery.com/)**
  Battery management software using adaptive charging algorithms to improve charging speed and battery lifespan.

- **[BatterMachine](https://www.batterymachine.com/)**
  Battery analytics and intelligence platform for EV fleets and energy storage systems.

- **[Voltaiq](https://www.voltaiq.com/)**
  Enterprise battery intelligence platform providing analytics, quality management, and performance optimization for battery manufacturers and operators.

- **[About:Energy](https://www.aboutenergy.io/)**
  Battery data and modeling platform providing cell characterization, battery models, and analytics for automotive and energy storage applications.

- **[Battery Cloud](https://www.batterycloud.com/)**
  Cloud-based battery monitoring and analytics platform.

- **[PowerUp](https://www.powerup.com/)**
  Battery analytics and management solutions for energy storage.

- **[Brill Power](https://www.brillpower.com/)**
  Intelligent battery management systems using cell-level power electronics for enhanced performance and lifespan.

- **[BMS PowerSafe](https://www.bmspowersafe.com/)**
  Battery management system solutions for industrial and energy storage applications.

- **[Stem](https://www.stem.com/)**
  AI-driven energy storage software and services for grid-scale and behind-the-meter applications.

- **[Ampcontrol](https://www.ampcontrol.io/)**
  AI-powered EV fleet charging and energy management software.

- **[Fluence Mosaic](https://www.fluencecorp.com/)**
  AI-powered bidding and optimization software for energy storage assets in wholesale markets.

- **[Banyan Infrastructure](https://www.banyaninfrastructure.com/)**
  Project finance software for sustainable infrastructure including energy storage.

- **[Nuvation Energy](https://www.nuvationenergy.com/)**
  Battery management systems and energy storage solutions for industrial applications.

- **[Yotta Energy](https://www.yottaenergy.com/)**
  Distributed energy storage solutions with integrated battery management.

- **[Enode](https://www.enode.com/)**
  API platform connecting energy devices including batteries to energy management applications.

- **[Piclo Flex](https://picloflex.com/)**
  Marketplace platform for flexibility services including battery storage.

## Open-Source GitHub Projects

- **[foxBMS 2](https://github.com/foxBMS/foxbms-2)**
  The first modular open-source BMS development platform, certified as open source hardware by OSHWA. Universal hardware and software platform for controlling modern electrical energy storage systems of any size including Lithium-Ion, Solid State, Sodium-Ion, Redox-Flow batteries, and Fuel Cells. BSD 3-Clause licensed with comprehensive documentation .

- **[BatPar](https://github.com/BatParDevleperTeam/BatPar)**
  Open-source battery parameterization toolkit with comprehensive user and developer manuals. Expected to facilitate broader adoption and improvement in battery management systems, energy storage solutions, and EV development .

- **[QuESt PCM](https://www.sandia.gov/ess/tools-resources/quest/quest-grid-planning-toolbox/pcm)**
  Open-source power system production cost modeling tool from Sandia National Laboratories. Provides high-fidelity representation of energy storage systems with cost-optimal dispatch, market participation simulation, and technology-specific storage models. Built in Python using Pyomo and EGRET .

- **[GridFlexPy](https://ieeexplore.ieee.org/abstract/document/11297666)**
  Open-source Python framework for power flow analysis and BESS operation in microgrids. Direct integration with OpenDSS, supports strategic allocation and operation of BESSs for demand smoothing and loss reduction. Validated on 14-bus microgrid test case showing 53% reduction in demand fluctuation .

- **[PyPESOL](https://dl.acm.org/doi/full/10.1145/3679240.3734691)**
  Python P2P Energy Sharing Optimization Library for cost optimization in peer-to-peer energy sharing scenarios. Supports individual and group-based cost optimization with battery usage decisions, peer matching algorithms, and battery/PV capacity modeling. Based on Pyomo and CBC LP solver .

- **[EMHASS](https://github.com/davidusb-geek/emhass)**
  Energy Management for Home Assistant with advanced battery and power management. Features intermediate battery SoC targets, battery-first priority, PV curtailment scheduling, battery SoC surplus cost for health preservation, demand charge calculations, and ML forecaster improvements .

- **[LibreSolar](https://github.com/LibreSolar)**
  Open-source hardware and firmware for battery management systems, MPPT solar charge controllers, and energy storage. Includes BMS designs for 5-15 Li-ion cells using TI bq769x0 analog frontends. Arduino-compatible libraries available .

- **[ShepherdBMS](https://github.com/Northeastern-Electric-Racing/Shepherd-BMS)**
  From-scratch Battery Management System application developed by Northeastern Electric Racing. Open-source BMS firmware with ADBMS integration .

- **[battery-degradation-prognosis](https://github.com/pnnl/battery-degradation-prognosis)**
  Tool for long-term prognosis of redox flow battery parameter degradation using Transformer-based deep learning models for time series forecasting. Developed by Pacific Northwest National Laboratory. MIT licensed .

- **[PolynomialSoH](https://github.com/iitis/PolynomialSoH)**
  Interpretable machine learning framework for battery State of Health estimation using graphene sensors. Includes code and datasets for SoH estimation experiments with temperature and resistance readings .

- **[Open-Source BMS Using ESP32-C3](https://ieeexplore.ieee.org/document/11632294)**
  Research presenting design and implementation of open, programmable, scalable BMS for LiFePO4 battery packs. Integrates ESP32-C3 microcontroller with BQ76920 AFE for cell voltage, current, and temperature monitoring. Includes passive cell balancing and overvoltage/undervoltage/short circuit protections .

- **[PVSizer](https://ieeexplore.ieee.org/abstract/document/11503109)**
  Open-source Python framework for PV and BESS sizing and impact analysis in distribution networks. Built on OpenDSS with modules for impact analysis, traversal for feasible domain mapping, and constraint-guided optimization. Validated on real utility feeder with 700+ nodes .

### Additional Strong Open-Source Options

- **OpenTerrace** — Python framework for packed bed thermal energy storage simulations .
- **QuESt Planning** — Long-term power system capacity expansion planning model identifying cost-optimal energy storage, generation, and transmission investments .
- **HeatBattery** — Open-source electronics and software for converting standard accumulators to smart heat batteries .
- **ibattery-sdk** — Embedded battery management SDK with BLE telemetry, SoC estimation, and Grafana dashboards for nRF52840, STM32, and ESP32 platforms .

**Frameworks for building custom battery management solutions**: Combine **foxBMS 2** for production-grade open-source BMS development with comprehensive hardware and software . Use **QuESt PCM** or **GridFlexPy** for BESS optimization and grid integration studies . Leverage **EMHASS** for home energy management with battery optimization . For P2P energy sharing research, **PyPESOL** provides modular optimization framework . For BMS prototyping, **LibreSolar** offers production-ready open hardware designs .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Battery management tools must comply with applicable safety standards and regulations for energy storage systems.
- Self-hosted open-source solutions require proper infrastructure, safety validation, and ongoing maintenance. Battery systems involve high voltages and currents — proper engineering expertise is essential.

---

**Made for battery engineers, energy storage developers, researchers, and BESS operators.**
Let's make battery energy storage management more open, transparent, and efficient.
