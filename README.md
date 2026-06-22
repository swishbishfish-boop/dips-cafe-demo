# Dip's Café — Demo Website + Dashboard

A demo restaurant/café site to show prospects: public menu page + an owner dashboard where they can upload a photo, name an item, set a price, and it appears live on the site — no developer needed.

## Stack (100% free tier)
- Frontend: plain HTML/CSS/JS, hosted free on GitHub Pages
- Backend: Supabase (free tier) — Postgres table `menu_items` + Storage bucket `menu-images`
- Auth: Supabase email/password (owner-only)

## Pages
- `index.html` — public menu, anyone can view
- `admin.html` — owner dashboard (login required)

## First-time setup for a new client
1. Open `admin.html`
2. Enter an email + password, click **"First time? Create admin account"**
3. You're in — add menu items with photos from here on
4. (Optional, more secure) In Supabase Auth settings, disable public sign-ups once the owner's account is created, so no one else can register as admin.

## Reselling this template
This is a clean template for any small restaurant/café:
- Swap branding/colors/text per client
- Each client gets their own Supabase project (free tier) + GitHub repo
- Domain is the only paid cost (~$10-15/year)
