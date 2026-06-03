# MD. REJAUL KARIM

**Senior Software Engineer — Native Android | Kotlin · Jetpack Compose · Hardware Systems · Flutter**

Dhaka, Bangladesh · +880 1724821030 · rejaul.karim.pro@gmail.com · [LinkedIn](#) · [Portfolio](#) · [GitHub](#)

---

## PROFESSIONAL SUMMARY

Senior Software Engineer with 7+ years delivering production-grade Native Android systems across ePOS/KDS commercial hardware platforms, EdTech at scale (100K+ MAU), and FinTech on-device ML pipelines. Core expertise spans low-level hardware IPC via AIDL, ESC/POS thermal rendering on Sunmi and Rockchip commercial SoCs, enterprise `.aar` SDK modularization, and Jetpack Compose performance architecture. Measurable delivery record: crash-free sessions lifted from 91% → 98.87%, 25% KYC onboarding conversion uplift, 19% booking conversion on a 360K+ user platform. Combines systems-level hardware integration depth with rigorous Clean Architecture discipline to ship high-reliability, maintainable software at sustained velocity.

---

## TECHNICAL SKILLS

**Languages:** Kotlin, Java, Dart

**Native Android:** Jetpack Compose, Material 3, Coroutines, Flow, StateFlow, SharedFlow, ViewModel, Navigation Component, WorkManager, Lifecycle, Paging 3, CameraX, ViewBinding

**Architecture & DI:** MVVM, MVI, Clean Architecture, Repository Pattern, SOLID, Modularization, Hilt, Koin, Dagger

**Hardware & Embedded POS:** ESC/POS Protocol, Sunmi SDK (NT311, D3 Pro, Cloud/Label Printers), Rockchip ctd-rk3288, AIDL (Inter-Process Communication), Bluetooth / USB / TCP/IP Thermal Printing, Barcode Scanning, Real-time Order Routing, Offline-first Sync

**SDK & Library Engineering:** `.aar` Modular SDK Architecture, Gradle Product Flavors, Multi-app SDK Distribution, API Abstraction Layer Design

**Flutter / Cross-Platform:** Flutter, Dart, Riverpod, BLoC, Cubit, Freezed, Dio, Hive, Isar, Platform Channels, Flavors

**Networking & APIs:** Retrofit, OkHttp, Ktor, REST, GraphQL, WebSocket, Interceptors, Token Refresh, Pagination

**Persistence:** Room, SQLite, ObjectBox, DataStore, SharedPreferences, Hive, Isar

**AI / ML:** ML Kit (Face Detection, OCR, Document Scan, NID Verification), TensorFlow Lite, On-device Inference, Prompt Engineering, LLM Integration (OpenAI, Gemini, Claude), AI-assisted Development (Cursor, Claude Code, Copilot)

**CI/CD & Release:** GitHub Actions, Firebase App Distribution, Gradle (KTS), Fastlane, Google Play Console, ProGuard / R8

**Analytics & Monitoring:** Firebase Crashlytics, Firebase Analytics, Mixpanel, WebEngage, Sentry, LeakCanary

**Testing:** JUnit, MockK, Espresso, Robolectric, Turbine, Compose UI Testing, Flutter Test

---

## PROFESSIONAL EXPERIENCE

### Senior Software Engineer (App Development)
**VALT** | Sylhet, Bangladesh | Feb 2026 – Present

- Spearheaded a full XML-to-Jetpack-Compose migration of the KDS application UI layer — reducing layout-related bug reports by ~40% and accelerating new screen delivery cycles by 35% — by eliminating view-binding overhead and deprecated imperative transition APIs, and engineering a declarative, state-driven component architecture with dynamic scaling and runtime theme-switching support targeting diverse commercial display hardware.

- Architected a universal thermal printer `.aar` library distributed project-wide across ePOS and KDS application modules, consolidating ESC/POS byte-stream generation and multi-transport negotiation (Bluetooth, USB, TCP/IP) behind a single abstraction interface — eliminating cross-team code duplication and reducing new printer-target integration effort to under two hours per transport variant.

- Engineered a thread-safe hardware IPC layer using Android Interface Definition Language (AIDL), decoupling print job lifecycle management from the application main thread and eliminating race conditions that caused printer state corruption under concurrent order bursts on Sunmi NT311 and D3 Pro commercial POS hardware.

- Designed a deterministic 80mm thermal receipt rendering pipeline optimized for Rockchip ctd-rk3288 SoCs, achieving sub-200ms end-to-end print latency under sustained transaction load through precision ESC/POS command batching and hardware-aligned buffer management within the AIDL service bridge.

- Designed an offline-first transaction processing architecture backed by Room DB with a reactive StateFlow-driven MVVM layer, guaranteeing zero data loss during network interruptions across POS workflows directly tied to restaurant revenue continuity.

- Refactored a fragmented, multi-module API layer by centralizing legacy Java service classes behind a unified Kotlin-first interface, standardizing error-handling contracts across all network boundaries and eliminating ~60% of scattered call sites across the ePOS and KDS codebases.

- Engineered real-time order routing and low-latency ticket display logic for the KDS application using Kotlin Coroutines and a Flow-based asynchronous state machine, sustaining deterministic kitchen-facing ticket updates and display integrity across multi-zone configurations under peak restaurant load.

---

### Senior Mobile Application Developer
**Repocket** | Singapore (Remote) | Nov 2025 – Jan 2026

- Engineered the Referral & Rewards feature end-to-end in Flutter / Dart — validated by a 15% user engagement uplift within the first month of launch — by designing a deep-link-aware referral graph with server-synchronized reward state and idempotent claim logic that eliminated reward duplication under network-retry conditions.

- Reduced funnel abandonment across referral steps by instrumenting targeted analytics events to surface per-step conversion drop-offs, producing behavioral data that directly informed two post-launch product iterations and improved overall referral completion rate.

- Delivered consistent cross-platform reliability across Android and iOS through widget-level testing, systematic Dart DevTools profiling, and async code review cycles within a distributed international engineering team.

---

### Specialist, Engineering — Android
**10 Minute School** | Dhaka, Bangladesh | May 2023 – Jun 2025

- Lifted crash-free session rate from 91% to 98.87% — recovering 7.87 percentage points of session reliability for a 100K+ MAU platform — through systematic root-cause triage via Firebase Crashlytics, exception-handling hardening at identified failure boundaries, and proactive pre-release regression monitoring across every quarterly release cycle.

- Drove full XML-to-Jetpack-Compose migration of the core EdTech application UI layer, accelerating new feature throughput by 20%, by eliminating imperative view-binding overhead, phasing out deprecated transition APIs (including `overridePendingTransition`) in favour of declarative animation orchestration, and establishing a lifecycle-correct, recomposition-aware component model.

- Architected a Compose-based design system comprising 30+ reusable, accessibility-compliant UI components, cutting design-to-dev handoff cycles and reducing accumulated UI design debt by 60% across all active product surfaces.

- Delivered end-to-end engineering ownership of the TARA adaptive learning app (Monash University research collaboration) — including a spaced-repetition content delivery engine, adaptive assessment layer, and interaction model for early childhood literacy and numeracy — from architecture through Play Store release.

- Integrated multi-layered analytics (Mixpanel, WebEngage) to instrument drop-off signals across purchase and learning funnels, producing behavioral data that directly shaped product prioritisation in quarterly planning cycles.

- Shipped 2–3 major production releases per quarter in close collaboration with UX, product, QA, and backend teams, sustaining consistent release cadence with zero regression incidents attributed to platform-layer changes.

---

### Associate Software Engineer — Android
**10 Minute School** | Dhaka, Bangladesh | Aug 2021 – May 2023

- Led Java-to-Kotlin migration of the monolithic Android codebase, improving null-safety guarantees, reducing incremental build times, and establishing idiomatic Kotlin patterns adopted as the engineering standard across all subsequent feature development.

- Engineered the booking system — achieving 19% conversion on a 360K+ registered user base and lifting class attendance from 16% to 35% — by architecting optimistic local state, WebSocket-driven real-time seat-availability updates, and transactional rollback logic on reservation failure.

- Built core EdTech product modules from scratch — live video classrooms, real-time chat, personalized learning workflows, and authentication — serving 100K+ active users with WebSocket-backed, low-latency communication channels and resilient session state management.

- Engineered gamified UI flows for academic student segments — increasing measured engagement by 12% — through micro-interaction patterns, progress-visibility mechanics, and streak-aware state management implemented in Jetpack Compose.

- Engineered an interactive exam and assessment module that improved student retention by 23% by implementing real-time scoring feedback, adaptive question sequencing logic, and persistent progress state backed by Room DB.

- Redesigned the course landing page in Jetpack Compose, driving a 13% uplift in course purchase conversion by restructuring CTA hierarchy and eliminating scroll-depth friction, informed by multi-layer behavioral analytics.

---

### Assistant Software Engineer — Android
**Millennium Information Solution Ltd.** | Dhaka, Bangladesh | Oct 2020 – Jul 2021

- Engineered a reusable `.aar` SDK integrating ML Kit on-device facial recognition, document OCR, and NID field verification — distributed across three FinTech banking apps (Social Islami Bank, Union Bank, Al-Arafah Islami Bank) via Gradle product flavors — reducing per-app KYC integration overhead from weeks to hours and enabling a single, auditable codebase for multi-tenant SDK delivery.

- Automated the full KYC onboarding pipeline using on-device ML inference (face liveness detection, document OCR, NID extraction), increasing average account creation rates by 25% across all three banking applications by eliminating the latency and error rate inherent to manual verification.

- Implemented self-registration flows delivering 50+ verified weekly user activations per application, by engineering multi-step form logic with inline validation, session-persistent state, and CameraX-backed document capture.

- Sustained high-compliance, zero-incident monthly feature delivery across three concurrent Android banking applications under Agile/Scrum cycles, maintaining strict release scheduling under regulatory timeline constraints.

---

### Junior Software Engineer — Android
**CodeNext Ltd.** | Dhaka, Bangladesh | Apr 2019 – Oct 2020

- Architected and shipped three B2B2C Android applications — Ichiiba wholesale marketplace, Salesman mobile app, and a tablet-optimized POS system — engineering a centralized API integration layer via Retrofit and OkHttp with request/response interceptors, transparent token refresh, and structured error-handling contracts across all network boundaries.

- Designed the tablet-optimized POS application with offline transaction queuing and multi-SKU barcode scan workflows, establishing early production expertise in POS/retail hardware interaction patterns directly foundational to subsequent ePOS system engineering.

- Published Ichiiba wholesale marketplace to Google Play Store, integrating Firebase Cloud Messaging for in-app re-engagement across a B2B2C multi-stakeholder user base (manufacturers, wholesalers, consumers).

---

### Android Developer
**Digital Internet Marketing** | Dhaka, Bangladesh | Apr 2018 – Oct 2018

- Delivered a production Android car rental application as first-career production software, engineering real-time booking state synchronization via Firebase Realtime Database and event-driven push notification delivery via FCM for low-latency booking management.

---

## SELECTED PROJECTS

**10 Minute School** — Native Android EdTech platform, 100K+ MAU. Live classes, real-time chat, gamified learning, booking system. Kotlin, Compose, MVVM, Room, Retrofit. [Play Store]

**TARA** — Adaptive learning app for early childhood literacy and numeracy, Monash University research collaboration. Full Android ownership: architecture through Play Store deployment. [Play Store]

**Repocket** — Cross-platform Flutter app (Android + iOS) for passive income. Referral & Rewards feature, +15% user engagement uplift. [Play Store]

**AIB i-Banking** — Secure FinTech banking app with ML Kit on-device KYC pipeline and self-registration. +25% account creation across three banking apps. [Play Store]

**SIBL Now** — Internet banking Android app for Social Islami Bank with secure authentication and fund transfer. [Play Store]

**Ichiiba Wholesale Marketplace** — B2B2C Android marketplace platform. Java/Kotlin, Retrofit, FCM, Room. [Play Store]

---

## EDUCATION

**Bachelor of Science, Computer Science & Software Engineering** | 2013 – 2018
American International University Bangladesh (AIUB) | Dhaka, Bangladesh | CGPA: 3.36 / 4.0
*Relevant Coursework: Data Structures & Algorithms, OOP, Software Architecture, Database Systems, Discrete Mathematics*

---

## CERTIFICATIONS

- Introduction to Prompt Engineering — Simplilearn (2025) [View]
- Advanced Android Application Development (Score: 82%) — Bangladesh Digital Skills / BDSkills (2024) [View]
- Top-up IT Training on Android Development — Bangladesh Computer Council (BCC) / ICT Division, validated by George Washington University (2018) [View]
- Training of Trainers (ToT), ICT Curriculum Delivery — BCC / NASSCOM-aligned (2018) [View]
- National Digital Innovation Program — Top 100 Participant — Banglalink Digital Communications (2017) [View]
- Droidcon Bangladesh — Android Development Conference (2017) [View]

---

## LANGUAGES

Bengali (Native) · English (Professional Working — C1 Listening/Writing, B2 Speaking) · Hindi/Urdu (Limited Working)
