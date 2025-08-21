+++
date = '2025-08-20T18:51:05-05:00'
draft = true
title = 'Contact'
+++
# Strategen — Build elite teams on demand

**Contact Us:**

**1) Clear purpose + primary CTA**

* One-liner: what visitors can contact you about.
* Primary button: **Book a demo** (calendar link) + secondary: **Contact sales**.

**2) Contact form (short and smart)**

* Required: **Full name**, **Work email**, **Company**, **Role**, **Topic** (Sales/Demo, Support, Partnerships, Press, Careers, Other), **Message**.
* Optional (helps qualification): **Team size** (select), **Timeline** (Now / 1–3 months / 3–6 months).
* **Consent**: “I agree to the Privacy Policy.” (link)
* Optional **marketing opt-in** (separate checkbox): “Send me product updates.”
* **Expected response time**: “We reply within 1 business day.”

**3) Direct channels**

* **Sales:** [sales@strategen.io](mailto:sales@strategen.io)
* **Support:** [support@strategen.io](mailto:support@strategen.io)
* **Partnerships/Press:** [partnerships@strategen.io](mailto:partnerships@strategen.io) / [press@strategen.io](mailto:press@strategen.io)
* **Phone** (if you’ll staff it reliably) and **hours** (America/Chicago).

**4) Company details**

* **HQ city/state**: Chicago, IL.
* Links: **Privacy Policy**, **Terms**, **Status**, **Careers**.

**5) Trust signals (optional but helpful)**

* 1–3 quick bullets on value (“Cut delivery time up to 50%…”).
* Customer logos or a short testimonial.
* Security note: “We never ask for passwords or sensitive data here.”

**6) Accessibility & anti-spam**

* Every input has a label, clear error text, keyboard navigation.
* Captcha or honeypot, basic rate limiting.
* Don’t request sensitive info (SSNs, credentials).

---

# Copy you can paste

**Hero**

> **Let’s build your strongest team**
> Have questions, want a demo, or need support? We’ll get back to you within **1 business day**.

**Form labels**

* Full name\*
* Work email\*
* Company\*
* Role
* Topic\* (Sales/Demo, Support, Partnerships, Press, Careers, Other)
* Team size (1–10, 11–50, 51–200, 200+)
* Timeline (Now, 1–3 months, 3–6 months)
* How can we help?\*

**Consent + SLA**

* ☐ I agree to the **Privacy Policy**.
* ☐ Send me product updates and news.
  *Sent! We typically respond within **1 business day**.*

**Alt contact**

> Prefer email? **[sales@strategen.io](mailto:sales@strategen.io)** for new projects, **[support@strategen.io](mailto:support@strategen.io)** for customers.

**Footer note**

> Strategen, LLC · Chicago, IL · We never ask for passwords or confidential data via this form.

---

# Implementation tips (for GitHub Pages now, Oracle Cloud later)

* On **GitHub Pages** (static), use a form backend (e.g., Formspree, Netlify Forms) or embed a calendar link for demos.
* For production on **Oracle Cloud**, point the form to an `/api/contact` endpoint (Oracle Functions/API Gateway), then send via SendGrid/SES and log to your CRM.

---

If you want, I can turn this into a **drop-in HTML/React block** that posts to a stub `/api/contact` and includes accessibility, error states, and a success toast.

