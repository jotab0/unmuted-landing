# Unmuted Landing Page — Version 2 Changelog

**Date:** February 11, 2026  
**File:** `index-v2.html`  
**Base:** `index.html` (Version 1)

---

## Changes Summary

### 1. Added Accent Colour (Terracotta #C08B70)

The landing page was too blank and lacked visual warmth. Following the brand guide, the **Terracotta** accent colour (`#C08B70`) — designated for CTAs and warm emphasis — was introduced throughout the page while keeping the editorial aesthetic intact.

**Specific changes:**
- **Primary buttons** (`.btn-primary`): Background changed from `--deep` to `--terracotta`, hover changed to `--earth`
- **Nav CTA button** (`.nav-cta`): Background changed from `--deep` to `--terracotta`
- **Hero headline italic** (`h1 em`): Color changed from `--earth` to `--terracotta`
- **Hero divider line**: Changed from 1px `--sand` to 2px `--terracotta`
- **Section heading italic** (`.section-heading em`): Color changed from `--earth` to `--terracotta`
- **Nav link hover underline**: Background changed from `--deep` to `--terracotta`
- **Stat numbers** (`.stat-number`): Color changed from `--black` to `--terracotta`
- **Secondary button hover**: Border color changed to `--terracotta`
- **Scroll animation line**: Background changed from `--earth` to `--terracotta`
- **Testimonial card hover**: Border color changed to `--terracotta`
- **Showcase heading em**: Color changed from `--blush` to `--terracotta`
- **FAQ active icon**: Color changed from `--earth` to `--terracotta`
- **Button box-shadow**: Adjusted to terracotta-tinted shadow

### 2. CTA Button Text & Link Updates

- **"Start Free"** changed to **"Contact Us"** in all instances:
  - Hero primary button
  - Nav CTA button
  - Final CTA section button
  - Mobile menu button
- **"See How It Works"** button in hero now links to `#showcase` (the "Same Creator. Two Languages. One Soul" section) instead of `#how-it-works`
- Added `id="showcase"` to the showcase section

### 3. Removed "Three Steps to Being Heard Everywhere" Section

The entire "How It Works" section (`#how-it-works`) with the three step cards (Upload, AI Learns, Publish) has been removed, including its surrounding divider lines.

**Also updated:**
- Navigation links: Removed "How It Works" link
- Mobile menu: Removed "How It Works" link
- Footer product links: Replaced "How It Works" with relevant links

### 4. Changed Features Heading

- **Before:** "We translate content, *not personality.*"
- **After:** "We translate personality, *not content.*"

### 5. Added YouTube Auto-Dub Comparison in Showcase Section

A **third comparison box** was added to the "Same Creator. Two Languages. One Soul" demo section to showcase how generic YouTube auto-dubbing sounds robotic compared to Unmuted's translation.

**Specific changes:**
- Demo grid changed from 2 columns to 3 columns
- New panel labeled **"Generic Auto-Dub"** with a `YouTube Auto-Dub — Spanish` translation
- Includes a description highlighting the flat, robotic, personality-less quality
- Panel styled with reduced opacity (0.7) and rose-muted accent to visually differentiate it as the "bad" example
- Badge reading "Generic Auto-Dub" added
- Responsive: Falls back to single-column on mobile

### 6. Removed Pricing Section

The entire pricing section (`#pricing`) has been removed, including:
- All three pricing cards (Starter, Creator, Studio)
- The "Need something custom?" note
- Surrounding divider lines

**Also updated:**
- Navigation links: Removed "Pricing" link, replaced with "The Difference" pointing to showcase
- Mobile menu: Removed "Pricing" link
- Footer: Replaced "Pricing" link with "The Difference" and "FAQ"

---

## Navigation Updates (combined from above)

**Before:** How It Works | Features | Pricing | FAQ  
**After:** Features | The Difference | FAQ

---

## Files

| File | Description |
|------|-------------|
| `index.html` | Original Version 1 (unchanged) |
| `index-v2.html` | Version 2 with all changes above |
| `CHANGELOG-v2.md` | This changelog |
