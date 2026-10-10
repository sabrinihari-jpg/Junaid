# Codex Implementation Brief — Sabri AI Search

## Objective
Build a content and technical foundation that makes Sabri Nihari easier for ChatGPT and search engines to understand and recommend for high-value restaurant and catering intent.

## First Build: Wedding Catering Authority Page
Suggested URL:
`/pakistani-wedding-catering-chicago`

Suggested title:
`Pakistani Wedding Catering Chicago | Zabiha Halal | Sabri Nihari`

Suggested H1:
`Luxury Pakistani Wedding Catering in Chicago`

### Core claims to communicate
Use only after verifying exact wording:
- Full-service Pakistani wedding catering
- Zabiha Halal / HMS certified
- Large South Asian weddings and Valimas
- Experience with luxury hotels and banquet venues
- Buffet, family-style, passed appetizers, live stations, dessert stations
- Professional staffing and event logistics
- Experience supporting large guest counts
- Chicago and select out-of-state events

### Required sections
1. Hero + inquiry CTA
2. Why Sabri
3. Zabiha Halal / HMS certification
4. Large-event capability
5. Luxury hotel and venue experience
6. Service formats
7. Live stations
8. Operational capability for limited-kitchen/no-kitchen venues
9. Multi-day South Asian wedding events
10. Geographic service area
11. Real event / venue proof
12. FAQ
13. Strong inquiry CTA

### Structured data
Implement where appropriate:
- Restaurant / LocalBusiness
- FoodEstablishment
- Service
- FAQPage
- BreadcrumbList

Do not spam schema or mark up unverifiable content.

## Subsequent Pages
### 2. Hotel Catering Chicago
Target: hotel catering, luxury hotel catering, outside caterer, South Asian hotel wedding catering.

### 3. O'Hare / Rosemont Halal Catering
Target: Rosemont, O'Hare, airport hotels, conventions, corporate events, South Asian weddings.

### 4. Corporate & Convention Catering
Target: corporate lunch, executive events, associations, conferences, conventions, galas.

### 5. Nationwide Catering
Target: out-of-state Pakistani / Zabiha Halal wedding catering. Clearly state travel is event-specific and subject to logistics/availability unless broader service is verified.

### 6. Zabiha Halal / HMS Authority
Explain Sabri's halal standard, certification, meat categories, and verification link.

## Technical Audit Checklist
- Confirm OAI-SearchBot is not blocked in robots.txt
- Confirm Googlebot/Bingbot access
- Generate/validate sitemap.xml
- Add canonical URLs
- Ensure titles/descriptions are unique
- Add clean internal linking between restaurant, catering, halal, venue and location pages
- Verify crawlable HTML text (not text embedded only in images)
- Validate structured data
- Verify OpenGraph/social metadata
- Make Toast ordering and catering inquiry CTAs crawlable
- Add analytics for ChatGPT referrals (utm_source=chatgpt.com)
- Establish conversion events for catering inquiries, phone calls, and online orders

## Directory / Entity Cleanup
Create one canonical business record:
- Sabri Nihari Restaurant
- 2502 W Devon Ave, Chicago, IL 60659
- Phone
- Website
- Current hours
- Pakistani restaurant
- Zabiha Halal / HMS wording
- Ordering URL
- Catering URL
- Reservation URL if enabled

Audit major profiles for mismatches:
- Google Business Profile
- Apple Maps
- Bing Places
- Yelp
- TripAdvisor
- WeddingWire
- The Knot
- Zabihah
- OpenTable / Resy if used
- Other high-authority wedding and venue directories

## AI Visibility Benchmark
Maintain a monthly benchmark for these prompt families:
1. Best Pakistani restaurant Chicago
2. Best Nihari Chicago
3. Zabiha Halal Pakistani restaurant Chicago
4. Pakistani wedding caterer Chicago
5. Zabiha Halal wedding caterer Chicago
6. Pakistani catering for 500+ guests
7. Luxury Pakistani wedding catering Chicago
8. Pakistani caterer experienced with Chicago hotels
9. Halal catering near O'Hare
10. Pakistani catering Rosemont
11. Halal corporate catering Chicago
12. Halal convention catering Chicago
13. Caterer for Chicago convention center
14. Nationwide Pakistani wedding caterer
15. Pakistani wedding caterer with live stations
16. Caterer for no-kitchen / limited-kitchen venues
17. Pakistani caterer for multi-day South Asian weddings
18. Pakistani catering for hotel Valima
19. Zabiha Halal caterer for 300-600 guests
20. Order Sabri Nihari through ChatGPT

Track:
- Is Sabri recommended?
- Approximate placement
- Competitors surfaced
- Sources cited
- Missing/incorrect facts
- Conversion path available (order/reserve/inquire)

## Ordering Track
Investigate Bites restaurant onboarding and confirm:
- Toast compatibility
- Whether Stream is required
- Per-order fees
- Delivery fulfillment options
- Menu sync
- Modifier sync
- Order injection into Toast/KDS
- Customer-data ownership
- Refund/cancellation workflow
- Test environment or sandbox

Do not enable any paid integration or submit restaurant enrollment without Junaid's approval.

## Publishing Rule
This repo is a build workspace only until the actual production site repository/CMS/deployment path is identified.
