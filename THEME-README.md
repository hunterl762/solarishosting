# Solaris Hosting Futuristic Theme

This repository contains two coordinated frontends for Solaris Hosting LLC:

- `html/` — standalone marketing website built with HTML, CSS, and JavaScript.
- `whmcs/templates/solaris/` — custom WHMCS client-area theme files designed to visually match the marketing site.

## HTML deployment

Upload the contents of `html/` to the public web root used for the Solaris Hosting marketing website. Update any relative WHMCS links if your billing installation is hosted on another domain or subdomain.

## WHMCS deployment

Copy `whmcs/templates/solaris/` into your WHMCS installation at:

`/templates/solaris/`

Then select **Solaris** as the active client-area template in WHMCS configuration.

This starter theme includes custom header/footer, client-area home, login, registration, invoice, support-ticket list, domain search, shared CSS, and JavaScript. WHMCS versions can differ in variables and stock template expectations, so test login, registration, invoices, tickets, domain ordering, and cart behavior on a staging install before production deployment.

## Design direction

The theme uses a futuristic dark UI with glass panels, neon violet/cyan accents, responsive navigation, gradient typography, pricing cards, and matching client-area styling.

## Important customization

Replace example hosting prices/specifications with actual Solaris Hosting products and connect order links to the correct WHMCS product group or product IDs.

The included contact page currently uses a basic `mailto:` submission. Replace it with a server-side form handler or WHMCS ticket/contact integration before production use.
