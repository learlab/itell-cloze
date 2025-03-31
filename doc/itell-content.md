# Extracting iTELL Content

We pulled page content and page summaries from Strapi using the following API call:
  - `data/strapi-pages.json`
    - `{{ _.STRAPI_URL }}/api/pages?fields[0]=Slug&fields[1]=PageSummary&populate=Content`
  - `data/strapi-page-summaries.json`
    - `{{ _.STRAPI_URL }}/api/pages?fields[0]=Slug&fields[1]=PageSummary`