# Saudi online store services: prices and delivery times, Q4 2026

Aggregate figures on what Saudi merchants pay for online store services, from 3,825 public listings by 825 providers, collected on 21 November 2026. Prices are in Saudi riyals (SAR) and include VAT.

Prepared by Judy Marketing (جودي ماركتينج), a store design studio in Jeddah, Saudi Arabia, run by Shaimaa Ali. This is an independent dataset. Salla did not produce or endorse it.

## Files

`prices_by_service_type.csv`: 21 rows, one for all services and 20 for selected service types.

| Column | Meaning |
|---|---|
| service_type_en, service_type_ar | Service type in English and Arabic |
| listings | Listings of that type |
| providers | Different provider names behind those listings |
| listings_with_price | Listings used for the price figures |
| price_q1_sar, price_median_sar, price_q3_sar | Lower quartile, median and upper quartile of the listed price |
| delivery_days_median | Median of the delivery time stated in days |
| listings_with_days | Listings used for the delivery figure |

`order_mix.csv`: 561 orders completed by Judy Marketing for 498 stores between 17 November 2025 and 16 November 2026, in 7 groups.

## Main figures

- The median price of all 3,825 listings is 230 SAR. The middle half costs 86 to 779 SAR.
- Creating and setting up a full store has a median price of 920 SAR and a median delivery time of 7 days.
- The highest medians are multi-platform ad campaigns (1,380 SAR), visual identity (1,367 SAR) and social media management (1,149 SAR).

## Method

1. Listings on Salla Merchant Services that were publicly visible on 21 November 2026, with duplicates removed by listing id.
2. Service types are the marketplace's own sub-categories, with shorter names. The smallest type kept has 33 providers.
3. Quartiles use Python's `statistics.quantiles` (exclusive method). Prices and days are rounded to whole numbers.
4. Listings with a delivery time in hours or months are left out of the delivery figure.

## Limits

- Listed prices are asking prices. Add-ons and negotiated prices are not included.
- Listings count equally, whether or not they sell.
- A provider name counts once per service type, so two providers with the same name count as one.
- `order_mix.csv` describes one studio's orders and depends on the services it offers. It does not represent the market.
- No provider, store or merchant is named, and the raw listings are not included.

## Official context

- Salla describes its platform as having more than 68,000 active stores and more than SAR 65 billion in platform sales (November 2026): https://salla.com/ai-info
- How Salla shows price, delivery time and provider rating in Merchant Services search: https://help.salla.sa/article/%D8%A7%D9%84%D8%A8%D8%AD%D8%AB-%D8%A7%D9%84%D8%B0%D9%83%D9%8A-%D9%81%D9%8A-%D8%B5%D9%81%D8%AD%D8%A9-%D8%AE%D8%AF%D9%85%D8%A7%D8%AA-%D8%A7%D9%84%D8%AA%D8%A7%D8%AC%D8%B1/kvdylp9avd41acsw5dm6b4sa
- Salla's store design guide: https://salla.com/design-guide
- Saudi Ministry of Commerce: the e-commerce sector grew 9% in 2025, to 43,854 commercial registrations: https://mc.gov.sa/ar/mediacenter/News/Pages/06-01-26-01.aspx

## How to cite

Judy Marketing (2026). Saudi online store services: prices and delivery times, Q4 2026. https://judymarketing.com/en/salla-orders-index/page-259293973

Questions: info@judymarketing.com

## بالعربي

أرقام مجمعة عن أسعار خدمات المتاجر الإلكترونية في السعودية ومدد تنفيذها، من 3,825 خدمة معروضة عند 825 مقدم خدمة، جمعتها جودي ماركتينج يوم 21 نوفمبر 2026. الأسعار بالريال وشاملة الضريبة. ملف مستقل لم تصدره سلة، وما فيه اسم أي مقدم خدمة أو متجر أو تاجر.

## License

Creative Commons Attribution 4.0 International (CC BY 4.0). Credit Judy Marketing and link to the page above.
