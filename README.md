# Hyundai Kona asking prices

Interactive chart and sortable table for public Yad2 Hyundai Kona listings, model year 2020 onward, including petrol, hybrid and electric.

Snapshot: 9 October 2026. 282 unique listings: 132 petrol, 121 hybrid, 29 electric. Petrol and hybrid are selected by default; use the independent fuel and km-range checkboxes to change both chart and table.

Point color runs from green (low mileage) to red (high mileage); the on-page color key labels all six bands. Marker shape identifies fuel: circle for petrol, diamond for hybrid, square for electric. Unknown mileage is gray.

Mileage comes from Yad2's own result-page km filter, not an exact odometer reading. Bands: 0-30K (54), 30-60K (73), 60-90K (60), 90-120K (64), 120-150K (21), 150K+ (10). These labels abbreviate inclusive query boundaries 0-30000, 30001-60000, 60001-90000, 90001-120000, 120001-150000, and 150001 upward. Representative band midpoints choose colors only. The open-ended top band is capped at the red end of the visual scale and does not assert actual mileage.

Refreshed against the 8 October snapshot: 31 added (29 electric, 2 petrol/hybrid), 5 no longer present. Presence changes are not proof of a sale. Listings were deduplicated by public ad token; promoted duplicates were not counted twice. No individual listing pages were opened and no login was used. One listing had no link available in the result page, so its link is marked unavailable.

Hover for listing details, click a chart point to open the ad, or use the sortable table. Listings without a price remain in the table. Eight raw result-page price values below ILS 10,000 are also retained and flagged in the table but excluded from the chart. Their meaning (monthly offer, placeholder or another reason) was not verified, so they must not be treated as full car asking prices. There are 259 chart-eligible prices across all fuels, 233 in the default petrol/hybrid view. Year positions are slightly spread to separate overlaps. Links can expire, and individual ad links were not independently opened. Prices are asking prices, not sale prices. Fuel/trim variants are mixed; this is not a valuation.

The page loads Plotly from a public CDN and needs internet access. Personal analysis, not affiliated with Yad2. The page and repository are public; no personal owner information, seller contact details or images are included.
