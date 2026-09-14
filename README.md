# Awesome-Patient-Engagement

## Top Patient Engagement Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Appointment Reminders, Digital Intake, Secure Messaging, Self-Scheduling, Recall & Patient Communication*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Patient Engagement**. These systems help healthcare practices and health systems communicate with patients via text, email, voice, and apps for scheduling, intake, reminders, secure messaging, recall, and care gap closure.



**Examples** include Luma Health, Phreesia, Solutionreach, Relatient, Weave, OhMD, Klara, Artera, PatientPop, and Rhinogram (the category leaders).



**Open-source emphasis**: Production patient engagement platforms are almost entirely commercial because of HIPAA, EHR integration depth, and operational reliability requirements. Useful open building blocks exist in patient portals, FHIR-based tools, and experimental engagement layers. This section lists the strongest available open resources and is realistic about the gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Luma Health](https://www.lumahealth.io/)**  

  Comprehensive patient engagement platform focused on access, self-scheduling, waitlists, reminders, and operational automation for practices and health systems.



- **[Phreesia](https://www.phreesia.com/)**  

  Leading digital intake, registration, and patient engagement platform with strong payment collection and EHR-integrated workflows.



- **[Solutionreach](https://www.solutionreach.com/)**  

  Long-standing patient communication platform specializing in appointment reminders, recall, and reputation management.



- **[Relatient](https://www.relatient.com/)**  

  Patient engagement and communication platform supporting messaging, scheduling, and outreach for healthcare organizations.



- **[Weave](https://www.getweave.com/)**  

  All-in-one communication platform popular with small practices (especially dental and optometry), combining phone, texting, payments, and reviews.



- **[OhMD](https://www.ohmd.com/)**  

  HIPAA-compliant two-way texting and patient communication platform designed for practice staff inboxes and modern messaging workflows.



- **[Klara](https://www.klara.com/)**  

  Patient communication and engagement platform (often used in specialty practices) supporting messaging, intake, and care coordination.



- **[Artera](https://artera.io/)**  

  Enterprise patient messaging and outreach platform focused on multi-channel, multi-language communication at health-system scale.



- **[PatientPop](https://www.patientpop.com/)**  

  Practice growth and patient engagement platform combining online presence, reputation, and communication tools.



- **[Rhinogram](https://www.rhinogram.com/)**  

  Secure patient messaging and engagement solution for healthcare practices.



## Open-Source GitHub Projects

- **[Opal](https://github.com/opalmedapps)**  

  Open-source patient-in-the-loop data platform that securely shares health data and explanations with patients in real time alongside care teams.



- **[Patient portal and engagement prototypes](https://github.com/)**  

  Community and academic projects offering health records access, medication tracking, lab results, wellness goals, and provider messaging.



- **[FHIR-native engagement experiments](https://github.com/)**  

  Emerging open efforts to build appointment reminders, secure messaging, and outreach on top of FHIR-compliant infrastructure.



- **[Open patient messaging and inbox tools](https://github.com/)**  

  Lightweight projects exploring secure or semi-secure messaging patterns suitable for healthcare communication prototypes.



- **[Appointment and recall open systems](https://github.com/)**  

  Simple scheduling, reminder, and recall tools that can be adapted for smaller or research-oriented deployments.



- **[Digital intake and form open frameworks](https://github.com/)**  

  Form and questionnaire platforms that support pre-visit data collection (require careful HIPAA configuration when used in care settings).



- **[Medplum and FHIR backend components](https://github.com/)**  

  Open FHIR-oriented infrastructure that can serve as a foundation for custom engagement features with significant engineering effort.



- **[Care-gap and outreach open analytics](https://github.com/)**  

  Tools for identifying patients due for follow-up and generating outreach lists from open data models.



- **[Multi-channel notification open libraries](https://github.com/)**  

  SMS, email, and voice notification components that can power basic reminder workflows when combined with compliant messaging providers.



- **[Patient experience open dashboards](https://github.com/)**  

  Visualization and feedback collection projects focused on measuring engagement and satisfaction.



### Additional Strong Open-Source Options

- Exploring **Opal** for patient-facing data sharing and transparency initiatives.

- Building research or internal prototypes on FHIR backends and open messaging components.

- Using open form and notification libraries for non-production or educational engagement flows.

- Accepting that deep EHR integrations, HIPAA-compliant two-way texting at scale, automated intake with payment collection, and proven no-show reduction still require commercial platforms.

- Combining open patient portals with commercial messaging when a hybrid approach is preferred.



**Frameworks for building custom systems**: Start with a FHIR-capable backend → add secure messaging and reminder logic → implement basic self-scheduling or intake forms → connect to compliant SMS/email providers → carefully manage consent, audit logs, and access controls. Suitable mainly for research, innovation labs, or highly resourced internal teams. Commercial platforms (Luma Health, Phreesia, OhMD, Weave, Solutionreach, Artera, Klara, etc.) remain the practical choice for most practices and health systems that need reliable, supported, integrated patient engagement.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Patient engagement systems handle protected health information (PHI) and must comply with HIPAA (or equivalent regulations). Open-source or self-built solutions require rigorous security, encryption, audit logging, Business Associate Agreements where applicable, and clinical workflow validation. Misconfigured systems can create privacy, safety, and legal risks. This list is not medical, legal, or compliance advice.



---

**Made for healthcare practices, health systems, and digital health teams who want better patient communication and access.**

Let's keep engagement patient-centered, secure, and as open as regulation allows.
