# sante.komun.org

[![sante.komun.org](/assets/media/logo.png)](https://sante.komun.org/)


## STEPS


### Local

- Design
  - GENERAL
    - `config.yml`
    - `data/*.{yml,md}`
  - If Multilanguaje and Multihosting, add `cp ./public/[es|en]/404.html ./public/` in `netlify.toml ⏩ build.command`
  - Try in Safari and Firefox
  - Check in [W3 Validator](https://validator.w3.org/)
  - Check in [PageSpeed Insights](https://pagespeed.web.dev/)


### After client validate web


#### Forms

- If Netlify Form
  - Don't need configure nothing! Build like you want in local or with CMS
  - [`Netlify ⏩ Site ⏩ Forms ⏩ Form Notifications`](https://app.netlify.com/sites/leandaovida/settings/forms#form-notifications) ⏩ `Add notification ⏩ Email notification ⏩ Email to Notify`
    - `Email to notify` = Emails of collaborators that want receive submissions
    - `Custom email subject line` = `Formulario de contacto de sante.komun.org`
    - `Save`
  - Submissions: [`Netlify site ⏩ Forms`](https://app.netlify.com/sites/leandaovida/forms)


#### [Google Search Console](https://search.google.com/search-console)

- Add property
- Verify versions ⏩ `data/config.yml`
  - `google_analytics`
  - `google_site_verification`
  - `google_file_verification`
  - DNS:
    From: `@`
    DNS Record: `TXT`
    To: `google-site-verification=[google_site_verification]`
- Link with Analytics
- Add sitemap.xml


#### [Google My Business](https://business.google.com/)

- `Add company ⏩ ...` ⏩ whait 13 days to receive postal and insert code to verify


##### Delivery

Send to all collaborators next:

```
*ENTREGA WEB sante.komun.org:* https://seacomoseo.com/entrega/
```
