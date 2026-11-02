# Automation & Website Portfolio
### Nathaniel Laxamana · AI Automation & GoHighLevel Specialist

I build systems for lead handling, follow-up, appointments, and connected business operations.

**[Live portfolio and evidence galleries](https://nathaniel-laxamana.vibepreview.app/)** · **[LinkedIn](https://www.linkedin.com/in/nathaniel-laxamana-392148313/)** · **[Contact](mailto:nclaxamana18@gmail.com)** · **[Book a call](https://calendly.com/nclaxamana18/30min)**

This repository documents my work. It is a project showcase, not a collection of runnable workflow exports. Source files and deployment instructions are included only when available and reviewed for sharing.

## Project catalog

| Project | Scope | Evidence / current status |
| --- | --- | --- |
| [AI-powered B2B lead processing](#ai-powered-b2b-lead-processing) | Seven-agent n8n/Gemini pipeline | Recorded demo and workflow canvas; self-built portfolio project |
| [WanderWise Travel](#wanderwise-travel) | Website, CRM, Conversation AI, four workflows, booking tracker | Recorded demo, website screenshots, and workflow screenshots; self-built demonstration |
| [Appointment lifecycle automation](#appointment-lifecycle-automation) | Intake through follow-up and appointment outcomes | Workflow canvas; implementation template |
| [Dental AI receptionist](#dental-ai-receptionist) | Administrative intake and calendar booking | Workflow canvas; template requiring configuration and testing |
| ApexShield Roofing | Roofing service landing page with lead capture, FAQ, and booking CTA | Website screenshots; self-built demonstration |
| DeepWell Infrastructure | Water-systems service page with service grid, pricing presentation, and booking path | Website screenshots; self-built demonstration |
| Confirmation & reminder workflow | GHL form entry, opportunity updates, tagging, email/SMS, and waits | Documented GHL workflow canvas |
| Appointment-status recovery workflow | GHL cancelled, no-show, and showed routing, tags, and follow-up | Documented GHL workflow canvas |
| GoHighLevel conditional follow-up | Contact-tag entry, waits, email/SMS, and conditional branching | Documented GHL workflow canvas |
| Pipeline stage change follow-up & tag routing | Pipeline-stage entry, timed messaging, branches, and tag updates | Documented GHL workflow canvas |
| Multi-stage contact follow-up & tag routing | Timed follow-up and nested tag-based conditions | Documented GHL workflow canvas |
| AI voice receptionist workflow | Call-start, assistant-request, and call-completed routing with contact/call logging | Implementation template; matching screenshot pending |
| Branded shoe order & inventory automation | Order processing and inventory synchronization concept | Implementation template; evidence pending |
| Mechanic-shop appointment & repair lifecycle | Appointment intake through repair completion | Implementation template; evidence pending |
| Meta AI inbox workflow | Facebook/Instagram inbox triage and replies | Implementation template; evidence pending |
| Personal AI inbox assistant | Inbox organization and reply drafting | Implementation template; evidence pending |
| Publishing editor-completion workflow | Manuscript routing and editor completion tracking | Implementation template; evidence pending |
| Writer/translator submission workflow | Submission intake and handoffs | Implementation template; evidence pending |
| Gemini-assisted job-application workflow | Application preparation with human review | Implementation template; evidence pending |

WanderWise's website and automation are one project. Its landing page, thank-you page, and workflows are grouped together rather than counted as separate projects.

## AI-powered B2B lead processing

**Status:** Self-built portfolio project. Production outcomes are unverified.

**Problem:** Leads from several sources need consistent validation, research, qualification, and handoff.

**Design:** Seven specialized agents handle validation, classification, research, enrichment, nurture, orchestration, and evaluation. Human review is retained before external communication.

**Tools:** n8n, Gemini, SerpApi, Apollo, Mailchimp, Gmail drafts, HubSpot, and Slack.

**Evidence:** [Watch the recorded demonstration](https://www.loom.com/share/37cf9606597b4369a2b9363766f17b9b). The live portfolio contains the surviving workflow canvas.

**Limit:** The original trial instance and workflow export are unavailable. The recording and canvas document the design; this repository does not contain a runnable export or verified production metrics.

## WanderWise Travel

**Status:** Self-built travel-business demonstration.

**Problem:** Demonstrate the full path from a travel consultation landing page to qualification, CRM follow-up, and booking records.

**Built:**
- Landing page and thank-you page.
- Multi-stage GoHighLevel CRM pipeline and contact tags.
- Maya Conversation AI qualification flow.
- Four GHL workflows: New Booking & Reminder; Appointment Outcomes; Booked & Confirmed; Post-consultation Follow-up.
- n8n appointment webhook → Edit Fields → Google Sheets → Gmail notification.

**Tools:** GoHighLevel, Conversation AI, n8n, webhooks, Google Sheets, and Gmail.

**Evidence:** [Watch the recorded demonstration](https://www.loom.com/share/b70f93ea2d944b3cb222e82dde85881f). The [live portfolio](https://nathaniel-laxamana.vibepreview.app/#work) groups the landing page, thank-you page, and all four workflow screenshots in its case study.

<details>
<summary>View selected WanderWise evidence</summary>

### Landing page
![WanderWise travel consultation landing page](https://vibe.filesafe.space/1793600688086825043/attachments/9fa2db97-a855-4420-948f-7cbecc9ecc7e.jpg)

### New booking and reminder workflow
![GoHighLevel booking confirmation and reminder workflow](https://vibe.filesafe.space/1793600688086825043/attachments/6bb25966-059f-45c6-a64c-de76d7fada07.jpg)

### Appointment outcome routing
![GoHighLevel cancelled, no-show, and showed appointment routing](https://vibe.filesafe.space/1793600688086825043/attachments/92866a03-8c2f-4787-aae6-2414bcfb05d7.jpg)

</details>

Marketing claims, testimonials, and offers inside demo website screenshots are sample website content, not verified client results.

## Appointment lifecycle automation

**Status:** Implementation template; requires configuration and testing.

A workflow design covering intake, qualification, booking, reminders, attendance, follow-up, rescheduling/cancellation, and errors.

**Tools:** n8n, Gemini, Google Sheets, Google Calendar, Gmail, and Slack.

The actual annotated workflow canvas is available in the live portfolio. Availability rules, credentials, communications, and exception paths must be configured and tested for each deployment. No production outcome is claimed.

## Dental AI receptionist

**Status:** Implementation template; workflow canvas documented; requires configuration and testing.

An administrative receptionist design using chat, WhatsApp, and voice webhooks, clinic configuration, calendar availability, explicit booking confirmation, and optional CRM/messaging/logging.

**Tools:** n8n, Google Calendar, channel webhooks, and optional CRM integrations. An external voice provider supplies telephony.

<details>
<summary>View actual n8n workflow canvas</summary>

![Dental AI Receptionist n8n workflow canvas](https://vibe.filesafe.space/1793600688086825043/attachments/5a9eae7f-b14c-4e5d-a79f-922c3149510c.jpg)

</details>

This is separate from the AI voice receptionist workflow listed above. The canvas is not evidence of a deployed clinic system or live-call performance.

## Websites & landing pages

- **ApexShield Roofing:** residential roofing demonstration with service/problem sections, trust content, FAQ, lead form, and booking CTA.
- **DeepWell Infrastructure:** water-systems demonstration with service cards, pricing presentation, and appointment booking path.
- **WanderWise Travel:** travel consultation landing page and thank-you page, documented with the same CRM case study above.
- **Personal portfolio:** [live website](https://nathaniel-laxamana.vibepreview.app/) featuring project galleries, responsive navigation, Calendly booking, and Formspree inquiries.

Website screenshots demonstrate page design and structure. Sample testimonials and business claims within demonstration pages are not personal client results.

## GoHighLevel workflow builds

The five additional GHL builds in the catalog have actual workflow screenshots in the live portfolio. Their descriptions refer to visible triggers, actions, and branches. A workflow canvas does not, on its own, prove successful execution or message delivery.

## Working approach

1. Understand the process and define the intended outcome.
2. Map triggers, data, conditions, handoffs, and failure paths.
3. Build and test the integration with clear validation.
4. Document the configuration and review the result.

## Contact

**Email:** [nclaxamana18@gmail.com](mailto:nclaxamana18@gmail.com)  
**Portfolio:** https://nathaniel-laxamana.vibepreview.app/  
**LinkedIn:** https://www.linkedin.com/in/nathaniel-laxamana-392148313/  
**Discovery call:** https://calendly.com/nclaxamana18/30min

Based in the Philippines · Calls: Monday–Friday, 8 AM–4 PM Philippine time (UTC+8).
