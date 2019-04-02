# **Google Accelerated Mobile Pages (AMP)**

Google Accelerated Mobile Pages are available with Vue Storefront 1.6. By default, the Product and Category pages do support AMP. To get the AMP page, you should use the following URL: `http://localhost:3000/c/hoodies-and-sweatshirts-24` -> `http://localhost:3000/amp/c/hoodies-and-sweatshirts-24`. The discovery links are added as `<link rel="amphtml" ...`. The landing pages then distribute the traffic to canonical Vue Storefront links to enable all the features to work (by definition, AMP doesn't support any additional JavaScript).

Important notice

AMP renderer works ONLY IN PRODUCTION MODE as the [Layouts and advanced output operations](https://docs.vuestorefront.io/guide/core-themes/layouts.html), specifically `index.html` template switching works only in production. In development mode, there can be CSR/SSR issues, so don't even test it in development mode 😃

AMPHTML templates are provided by the `src/themes/default-amp` special purpose theme, which inherits some parts from the `default` theme.


<!-- Docs to Markdown version 1.0β16 -->


Using this Markdown file:

1. Cut and paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β16
* Tue Apr 02 2019 05:04:22 GMT-0700 (PDT)
* Source doc: https://docs.google.com/a/divante.pl/open?id=1oN_ipwhykk1YoK5vWCLE0o-19uQ-tnYs2XJgFku6oUg

