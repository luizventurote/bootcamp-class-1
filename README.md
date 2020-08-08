# Shopify Bootcamp

## Config file example

Use the file `config.yml` to connect with Shopify instances:

```
development:
  password: PASSWORD
  theme_id: "THEME_ID"
  store: STORE_NAME.myshopify.com
production:
  password: PASSWORD
  theme_id: "THEME_ID"
  store: STORE_NAME.myshopify.com
  timeout: 1m0s
  ignore_files:
  - config/settings_data.json
```