# DocBrain Marketing Data

Public mirror of outreach lead files from `plugins/docbrain-marketing/data/`.

---

## Europe retail outreach

| Metric | Count |
|--------|------:|
| Leads | 3000 |
| Exportable emails | 2975 |
| Leads with website | 2906 |

| File | Description |
|------|-------------|
| [outreach/europe-retail-leads-emails.json](outreach/europe-retail-leads-emails.json) | JSON: `{ email, website, name, city, country }` |
| [outreach/europe-retail-leads-emails.txt](outreach/europe-retail-leads-emails.txt) | Tab-separated: `email<TAB>website` |
| [outreach/europe-retail-leads-brevo.csv](outreach/europe-retail-leads-brevo.csv) | Brevo: `EMAIL,FIRSTNAME,LASTNAME,WEBSITE` |
| [outreach/europe-retail-leads.csv](outreach/europe-retail-leads.csv) | Full leads with website, city, category |

---

## FedEx — WooCommerce stores (WordPress + FedEx shipping)

**ICP:** Ecommerce sites running **WordPress + WooCommerce** that **ship with FedEx**.

| File | Description |
|------|-------------|
| [fedex/fedex-woocommerce-leads-emails.json](fedex/fedex-woocommerce-leads-emails.json) | Emails + website (copy-paste JSON) |
| [fedex/fedex-woocommerce-leads-emails.txt](fedex/fedex-woocommerce-leads-emails.txt) | `email<TAB>website` |
| [fedex/fedex-woocommerce-leads-brevo.csv](fedex/fedex-woocommerce-leads-brevo.csv) | Brevo import |
| [fedex/fedex-woocommerce-stores.json](fedex/fedex-woocommerce-stores.json) | All verified stores (website list, even if no public email) |
| [fedex/fedex-woocommerce-leads.csv](fedex/fedex-woocommerce-leads.csv) | Full CSV with WP/WC/FedEx flags |

Regenerate locally: `npm run scrape:fedex` (target 6000 emails, resume-safe). See `scripts/README-fedex-leads.md`.

---

## Other

| File | Description |
|------|-------------|
| `outreach/beauty-business-los-angeles-ca-*` | LA beauty sample |
| `outreach/europe-retail-leads-master.json` | Europe scraper resume state |
| `outreach/europe-scrape.log` | Europe scraper log |

`leads.json` (DocBrain signups / Stripe) is **not** included for privacy.

## License

Lead data scraped from public business websites for B2B outreach research.
