# LOOMO release compliance checklist

**Status: NOT CLEARED FOR ERP SOURCE PUBLICATION OR PROPRIETARY INTEGRATION DISTRIBUTION.** This checklist is a preparation aid, not a legal opinion.

## ERPNext-derived community release

- [ ] Obtain partner's Git repository (including history, upstream remote/version or fork relationship).
- [ ] Compare exact ERPNext upstream tag/commit with LOOMO's source and document changes, including branding.
- [ ] Review the applicable ERPNext GPL-3.0 license file and preserve it and upstream copyright and contributor notices.
- [ ] Review every included dependency, application, asset, icon, image and font for license and redistribution permissions.
- [ ] Ensure no Frappe or ERPNext logo/artwork is reused as LOOMO branding without permission; use upstream names factually, without implying endorsement.
- [ ] Check Git history and working tree for credentials, customer data, tokens, signing keys and private code; rotate secrets if exposed.
- [ ] Verify build/install instructions and availability of corresponding source for distributed GPL components.
- [ ] Check documentation copyrights and asset licenses separately from source-code licenses.
- [ ] Verify public release contents, contributors' rights, and third-party notices.
- [ ] Seek qualified software licensing/legal review before source publication.

## LOOMO AGENT and commercial integrations

- [ ] Identify the exact Paperclip revision and preserve MIT copyright/license notices and other third-party licenses.
- [ ] Create an architecture diagram showing processes, communication mechanisms and source-code dependencies.
- [ ] Evaluate whether the AGENT–ERP coupling creates a combined GPL-covered work before distributing proprietary software.
- [ ] Document customer rights, terms of service, hosted vs distributed deployment, licenses and support terms.
- [ ] Obtain legal review of commercial licensing and trademark/branding claims.

## GitHub governance

- [ ] Set up organization owners, minimum necessary access, 2FA and recovery procedures.
- [ ] Enable branch protection/rulesets, secret scanning and dependency alerts where available.
- [ ] Establish security reporting, contribution policy and release approval process for the actual ERP repository.
- [ ] Provide a verified business contact address; do not invent an email.
- [ ] Maintain accurate roadmap labels: planned vs shipped.

**Primary references:** [Frappe license and trademark policy](https://docs.frappe.io/legal/others/license-and-trademark), [ERPNext upstream](https://github.com/frappe/erpnext), [GNU GPL FAQ](https://www.gnu.org/licenses/gpl-faq.en.html), [Paperclip upstream](https://github.com/paperclipai/paperclip).
