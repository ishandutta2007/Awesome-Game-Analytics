# Awesome-Game-Analytics

## Top Game Analytics Tools Ecosystem

**Curated List of SaaS/Commercial Products & Open-Source GitHub Projects**  
*Focused on In-Game Event Tracking, Player Behavior, Retention, Monetization, Attribution & Product Analytics for Games*  
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Game Analytics**. These tools help game studios and publishers track player events, understand behavior and retention, measure monetization, run attribution, and gain actionable insights across mobile, PC, console, and live-service titles.

**Examples** include GameAnalytics, Unity Analytics, DeltaDNA, PlayFab Insights, Amplitude, Mixpanel, Devtodev, Adjust, AppsFlyer, Singular, GameRefinery, and Data.ai (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted product and game analytics — ideal for studios that want full data ownership, unlimited events, and freedom from usage-based pricing.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[GameAnalytics](https://www.gameanalytics.com/)**  
  Popular free-to-start game analytics platform purpose-built for mobile and multi-platform titles, with strong event tracking, progression, and monetization insights.

- **[Unity Analytics](https://unity.com/products/unity-analytics)**  
  Built-in analytics solution for Unity games covering player behavior, retention, and performance within the Unity ecosystem.

- **[DeltaDNA](https://deltadna.com/)** (now part of Unity)  
  Player analytics and engagement platform historically strong in behavioral segmentation and live-ops insights for games.

- **[PlayFab Insights](https://playfab.com/)**  
  Analytics and data capabilities within Microsoft’s PlayFab backend services for live games.

- **[Amplitude](https://amplitude.com/)** & **[Mixpanel](https://mixpanel.com/)**  
  Leading general product analytics platforms widely used by game studios for deep funnel, retention, cohort, and behavioral analysis.

- **[Devtodev](https://www.devtodev.com/)**, **[Adjust](https://www.adjust.com/)**, **[AppsFlyer](https://www.appsflyer.com/)**, **[Singular](https://www.singular.net/)**  
  Specialized mobile measurement, attribution, and game analytics platforms focused on UA, ROAS, and cross-channel insights.

- **[GameRefinery](https://www.gamerefinery.com/)**, **[Data.ai](https://www.data.ai/)**  
  Market intelligence and competitive analytics tools that complement first-party game analytics with industry and competitor data.

## Open-Source GitHub Projects

- **[PostHog](https://github.com/PostHog/posthog)**  
  Leading open-source product analytics platform (MIT) offering event tracking, funnels, retention, cohorts, session replay, feature flags, and experiments. Highly suitable for game studios that want a full self-hosted analytics stack.

- **[Countly](https://github.com/Countly/countly-server)**  
  Open-source product analytics platform with strong mobile and multi-platform support, push notifications, crash reporting, and plugins — well-suited for games.

- **[OpenPanel](https://github.com/Openpanel-dev/openpanel)**  
  Privacy-first, self-hostable product analytics tool designed as a Mixpanel/Amplitude-style alternative with modern event and user insights.

- **[Matomo](https://github.com/matomo-org/matomo)**  
  Mature open-source analytics platform (web + product plugins) that can be extended for custom event tracking and on-premise game or player analytics.

- **[Umami](https://github.com/umami-software/umami)** & **[Plausible](https://github.com/plausible/analytics)**  
  Lightweight, privacy-focused open-source analytics solutions useful for web-based games, landing pages, and simpler event tracking needs.

- **[Game-specific event & achievement trackers](https://github.com/)**  
  Emerging open-source projects for stats, achievements, and real-time event logging tailored to indie game and SaaS developers (e.g., TrakrLog-style tools and openstats prototypes).

- **[Custom event pipelines & SDKs](https://github.com/)**  
  Open-source collectors, SDKs, and warehouse-centric approaches (often built on ClickHouse, Kafka, or similar) that studios use to build internal game analytics platforms.

### Additional Strong Open-Source Options

- Self-hosted session replay and heatmapping tools paired with event data.
- Open-source attribution and deep-linking components for mobile games.
- dbt + warehouse models for custom game KPIs (DAU/MAU, retention curves, LTV).
- Many studio-internal analytics frameworks that are partially released as open source.

**Frameworks for building custom systems**: Start with **PostHog** for a complete open-source product analytics experience that covers most game needs (events, retention, funnels, flags). Use **Countly** when mobile-first or plugin extensibility is important. For lighter or privacy-first requirements consider **OpenPanel**, **Matomo**, or **Umami**. Larger studios often combine an open analytics core with a data warehouse and custom game-specific models.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/commercial or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Game analytics often involves high event volumes, real-time requirements, and player privacy considerations (COPPA, GDPR, etc.). Self-hosted open-source solutions give full control but require capacity planning, data governance, and ongoing maintenance. Commercial platforms frequently provide game-specific metrics, SDKs, and support that pure open-source stacks may need additional engineering to match.
- Always design event taxonomies carefully and respect platform and regional privacy rules when instrumenting games.

---

**Made for game studios, live-ops teams, and indie developers seeking open, controllable analytics.**  
Let's make player insights more transparent and studio-owned.
