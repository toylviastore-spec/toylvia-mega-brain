# ✅ Restore Point — Toylvia AI Brain
**Saved:** 2026-05-09

---

## 👤 Owner Identity
- **Owner email:** zikobooking@gmail.com
- **Shopify store slug:** `toy-liva` (admin URL: `https://admin.shopify.com/store/toy-liva/`)
- **Shopify store domain:** `toy-liva.myshopify.com`
- **Storefront domain:** `toylvia.com`
- **Live theme ID:** `199513243979`

---

## 🔌 Connected MCP Servers

### 1. Shopify MCP
- **Store:** Toylvia (`toylvia.com`)
- **Store slug:** `toy-liva` ← use this for CLI and admin URLs, NOT `toylvia`
- **Admin URL:** `https://admin.shopify.com/store/toy-liva/`
- **Myshopify domain:** `toy-liva.myshopify.com`
- **Live theme ID:** `199513243979`
- **Plan:** Basic
- **Currency:** USD
- **Timezone:** CEST
- **Country:** Slovenia
- **Status:** ✅ Connected & Operational
- **Capabilities:** Read + Write (products, orders, customers, collections, discounts, inventory, GraphQL)
- **⚠️ Limitation:** MCP blocks `themeFilesUpsert` on live/MAIN theme — use Shopify CLI or admin UI for theme file edits

### 2. Windsor.ai MCP
- **Account:** toylvia.store@gmail.com
- **Status:** ✅ Connected & Operational
- **Note:** Free trial — max 9 fields per data preview query

#### Connected Google Sources (all flowing live data):
| Source | Account ID | Status |
|--------|-----------|--------|
| Google Ads | 282-450-0635 (Toylvia) | ✅ Live |
| Google Analytics 4 | 524112161 (toylvia.com) | ✅ Live |
| Google Merchant Center | 5692443679 (Toyliva) | ✅ Live (use `product_performance_date` + product metric fields separately from product attribute fields) |
| Google Search Console | https://toylvia.com/ | ✅ Live |

---

## 🛠️ Installed Skills

### Shopify AI Toolkit (19 skills) — `Shopify/shopify-ai-toolkit`
Installed via: `npx skills add Shopify/shopify-ai-toolkit --yes`

- shopify-admin
- shopify-app-store-review
- shopify-custom-data
- shopify-customer
- shopify-dev
- shopify-functions
- shopify-hydrogen
- shopify-liquid
- shopify-onboarding-dev
- shopify-onboarding-merchant
- shopify-partner
- shopify-payments-apps
- shopify-polaris-admin-extensions
- shopify-polaris-app-home
- shopify-polaris-checkout-extensions
- shopify-polaris-customer-account-extensions
- shopify-pos-ui
- shopify-storefront-graphql
- shopify-use-shopify-cli

---

## 📝 Known Notes
- Google Merchant Center: performance metrics (`product_clicks`, `product_impressions`, `product_ctr`) must be queried separately from product attributes (`product_title`, `product_price`, etc.)
- Windsor.ai free trial limits data previews to **9 fields max** per query
- Computer use: Windows PowerShell granted at tier "click" (no typing — use Bash tool for commands)

---

## 🔁 To Restore This State
1. Ensure Shopify MCP is connected
2. Ensure Windsor.ai MCP is connected (reconnect if dropped)
3. Skills are installed at: `~\OneDrive\Desktop\Toylvia Mega-Brain\.agents\skills\`
4. Re-run `npx skills add Shopify/shopify-ai-toolkit --yes` if skills are missing
