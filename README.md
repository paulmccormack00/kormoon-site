# Kormoon Static Site

This is a static HTML version of the Kormoon website, converted from WordPress for free hosting on Netlify, GitHub Pages, or Cloudflare Pages.

## Files Included

- `index.html` - Main homepage with acquisition announcement, journey narrative, and product information
- `privacy-notice.html` - Privacy notice page
- `cookie-notice.html` - Cookie notice page  
- `website-terms.html` - Website terms of use
- `images/` - All original images including astronaut illustrations, product screenshots, and banners
- `favicon/` - Favicon files for all platforms

## Deployment to Netlify (Recommended - Free)

### Option 1: Drag and Drop (Easiest)
1. Go to https://app.netlify.com/drop
2. Drag the entire `kormoon-static` folder onto the page
3. Wait for deployment (takes ~30 seconds)
4. Your site is live at a random netlify.app URL

### Option 2: Connect Custom Domain
1. After deploying, go to Site settings → Domain management
2. Click "Add custom domain"
3. Enter: kormoon.ai
4. Update DNS at Eurodns:
   - Option A: Change nameservers to Netlify's nameservers
   - Option B: Add CNAME record pointing to your Netlify URL

### DNS Settings for kormoon.ai at Eurodns
If keeping Eurodns nameservers, add these records:
- Type: A, Name: @, Value: 75.2.60.5
- Type: CNAME, Name: www, Value: [your-site].netlify.app

Netlify will automatically provision a free SSL certificate.

## Alternative Free Hosting Options

### GitHub Pages
1. Create a new repository on GitHub
2. Upload all files
3. Go to Settings → Pages
4. Enable GitHub Pages from main branch
5. Add custom domain in settings

### Cloudflare Pages
1. Go to https://pages.cloudflare.com
2. Connect to Git or upload directly
3. Configure custom domain

## Cost Summary

| Item | Before | After |
|------|--------|-------|
| Ionos Hosting | £30.74/month | £0 |
| PHP Extended Support | £15.62/month | £0 |
| kormoon.ai domain | ~£25/year | ~£25/year |
| **Total Annual** | **£369/year** | **~£25/year** |

**Annual Savings: ~£344**

## After Migration Checklist

- [ ] Deploy to Netlify
- [ ] Configure kormoon.ai DNS
- [ ] Test all pages and links
- [ ] Cancel Ionos Web Hosting Pro (contract 85521696)
- [ ] Cancel PHP Extended Support
- [ ] Cancel auto-renewal on unused domains at Ionos
- [ ] Cancel/let expire domains at GoDaddy and Eurodns (except kormoon.ai)

## Support

For any issues with this static site, the original WordPress theme files are preserved in your backup.
