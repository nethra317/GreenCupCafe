# Green Cup Café — Single Page (Assignment Submission)

**Stack:** HTML5 + Tailwind CSS (CDN) + Vanilla JavaScript  
**Location used in copy:** Bangalore, India

## Files
- `index.html` — main page (includes SEO meta tags + Open Graph)
- `script.js` — mobile menu, form validation, small UI behavior
- Images are embedded via Unsplash URLs (no local image files required)

## How to run locally
1. Save files in a folder `green-cup-cafe/`.
2. Open `index.html` in your browser (no build step needed).

## Deployment (quick options)
**Netlify (drag-and-drop)**
1. Go to https://app.netlify.com/drop
2. Drag the folder (or zipped folder) and drop it.
3. Wait for automatic deploy, copy the generated URL and submit it.

**Vercel (via GitHub)**
1. Create a GitHub repo (e.g. `green-cup-cafe-yourname`) and push files.


### Part 1 — Website
- Live URL: https://green-cup-cafe.netlify.app/ 
- GitHub/ZIP: https://github.com/nethra317/GreenCupCafe.git

### Part 2 — SEO Basics
**Suggested Homepage Titles (3):**
1. Green Cup Café – Freshly Brewed Coffee & Cozy Atmosphere in Bangalore  
2. Best Coffee Shop in Bangalore | Green Cup Café  
3. Green Cup Café – Specialty Coffee, Organic Beans, and Friendly Service

**Target Keywords (5):**
- coffee shop Bangalore  
- best café in Bangalore  
- organic coffee beans  
- latte art café  
- specialty coffee drinks
- Impo: The actual `<title>` and meta description are present in `index.html`. Use the alternate titles within page content or test them in A/B tests.

### Part 3 — Social Media & Digital Marketing
**Instagram caption (≤ 30 words):**  
☕ Our new coffee menu is here! Taste the richness of freshly brewed perfection at Green Cup Café. Come sip, relax, and enjoy the vibe!

**Suggested hashtags (2):**
- #GreenCupCafe  
- #CoffeeLovers

### Part 4 — Analytics Awareness
**Tool:** Google Analytics 4 (GA4)  
**Why:** GA4 is free and provides cross-device event-based tracking, traffic source insights, and conversion measurement which help optimize marketing and improve the customer experience.

**How to add GA4:**  
1. Create GA4 property in Google Analytics.  
2. Install the GA4 tag (gtag.js) in the `<head>` of `index.html`. Example:
```html
<!-- GA4 placeholder (replace G-XXXXXXX with your ID) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXX"></script>
<script>
window.dataLayer = window.dataLayer || [];
function gtag(){dataLayer.push(arguments);}
gtag('js', new Date());
gtag('config', 'G-XXXXXXX');
</script>
