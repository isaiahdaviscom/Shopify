# Shopify
Theme development

https://shopify.github.io/themekit/


# https://shopify.github.io/themekit/configuration/
development:
  password: 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
  theme_id: "116496990378"
  store: the-mac-cheese-bar.myshopify.com
  proxy: http://localhost:3000
  ignore_files:
    - "*.gif"
    - "*.jpg"
    - config/settings_data.json
production:
  password: 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
  theme_id: "116496990378"
  store: the-mac-cheese-bar.myshopify.com
  timeout: 60s
  readonly: true
test:
  password: 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
  theme_id: "116496990378"
  store: the-mac-cheese-bar.myshopify.com
  ignores: ignore.txt