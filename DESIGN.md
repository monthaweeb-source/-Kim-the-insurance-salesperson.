---
name: Kim Insurance Agent System
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#43474d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#74777e'
  outline-variant: '#c3c6ce'
  surface-tint: '#49607c'
  primary: '#001428'
  on-primary: '#ffffff'
  primary-container: '#0f2942'
  on-primary-container: '#7991af'
  inverse-primary: '#b0c9e8'
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#86f2e4'
  on-secondary-container: '#006f66'
  tertiary: '#1f1000'
  on-tertiary: '#ffffff'
  tertiary-container: '#3b2200'
  on-tertiary-container: '#c77f00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d1e4ff'
  primary-fixed-dim: '#b0c9e8'
  on-primary-fixed: '#011d35'
  on-primary-fixed-variant: '#314863'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: plusJakartaSans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: plusJakartaSans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: plusJakartaSans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: plusJakartaSans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: 0em
  headline-sm:
    fontFamily: plusJakartaSans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0em
  body-lg:
    fontFamily: plusJakartaSans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0em
  body-md:
    fontFamily: plusJakartaSans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: plusJakartaSans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: plusJakartaSans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: 0.01em
  label-md:
    fontFamily: plusJakartaSans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: plusJakartaSans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.25rem
  space-xl: 1.5rem
  space-2xl: 2rem
  space-3xl: 2.5rem
  space-4xl: 3.5rem
  margin-mobile: 1rem
  margin-tablet: 1.5rem
  gutter-mobile: 0.75rem
  gutter-desktop: 1.5rem
---

## Brand & Style

This design system delivers a personal, advisory insurance experience tailored for Thai consumers navigating life, health, and savings policies. Built on the philosophy of the "knowledgeable neighbor," it balances corporate credibility with conversational warmth. The aesthetic rejects the clinical, intimidating red-tape tropes of legacy underwriters in favor of an approachable, transparent advisory aesthetic—combining crisp modernist layouts with soft, welcoming tactile contours.

### Key Tenets
- **Authoritative Warmth:** Reassures users through institutional blue foundations while humanizing the interaction using vibrant, optimistic amber touchpoints.
- **Thai-First Legibility:** Generous vertical line-heights and open letterforms tailored specifically to accommodate tone marks and vowels above and below the baseline without clipping.
- **Decision Clarity:** Heavy use of digestible bite-sized cards, prominent value takeaways, explicit benefit badges, and frictionless comparative structures.
- **Frictionless Accessibility:** Touch targets optimized for one-handed mobile interactions (min 48px), high-contrast labels, and clear financial summaries.

## Colors

The palette uses a classic tri-color operational architecture specifically balanced for advisory trust and conversion momentum:

- **Primary (`#0F2942` - Royal Deep Navy):** Anchors primary brand headers, authoritative navigation, primary data labels, and deep structural surfaces. Communicates long-term stability and solvency.
- **Secondary (`#0D9488` - Deep Sea Teal):** Serves as the functional affirmation and technical accent color—used for active plan comparisons, approved state badges, coverage checkmarks, and secondary utility triggers.
- **Tertiary (`#F59E0B` - Warm Sunlight Amber):** Exclusively reserved for high-intent customer actions, personalized consultation CTAs ("ปรึกษาคิมฟรี", "เปรียบเทียบแผน"), urgency tags, and advisory spotlights.
- **Neutrals & Surfaces (`#F8FAFC` to `#0F172A`):**
  - Surface Base: `#F8FAFC` (Canvas backdrop)
  - Surface Raised / Card: `#FFFFFF`
  - Surface Subdued: `#F1F5F9` (Muted input fills and comparative column stripes)
  - Border Subdued: `#E2E8F0`
  - Text Primary: `#0F2942` (Deep Navy replacement for stark black)
  - Text Secondary: `#475569` (Slate for subtext and policy fine print)

## Typography

Typography relies on geometric balance with generous line heights to gracefully support Thai script diacritics (วรรณยุกต์ และ สระบน-ล่าง) alongside English numerals and terms.

- **Vertical Line Clearance:** All line-heights are expanded by 25–35% compared to standard Latin typography to prevent stacked clipping of Thai vowels (`่`, `้`, `๊`, `๋`, `ิ`, `ี`, `ึ`, `ื`, `ุ`, `ู`).
- **Numbers and Currency:** Premium figures (e.g., "฿15,000/ปี") use semi-bold weights with standard tabular alignment for effortless scanning in comparative pricing lists.
- **Hierarchy Rules:** Never use body text below 12px for critical policy exclusions. Micro-labels are strictly reserved for non-essential auxiliary tags.

## Layout & Spacing

A mobile-first, 4-column layout model with 16px lateral safe gutters. On tablet viewports (768px+), it expands into an 8-column system, and desktop caps at a contained 12-column 1140px width centered on canvas.

### Rules & Rhythm
- **Rhythm Multiplier:** Standard base unit of 4px / 8px. Card content padding uses `1.25rem` (20px) to balance edge-to-edge density on compact devices like the iPhone SE.
- **Tap Clearance:** Interactive actions (buttons, selection tabs, phone triggers) maintain an intrinsic touch target height of at least `48px`, surrounded by `8px` clear boundaries.
- **Sticky Actions:** Critical consultation triggers are anchored inside a bottom fixed bar with `space-md` safe-area padding for one-thumb reachability.

## Elevation & Depth

This system avoids harsh drop shadows in favor of ambient navy-tinted occlusion shadows that feel organic and daylight-lit:

- **Level 0 (Flat / Canvas):** Surface color `#F8FAFC` without shadow; used for foundational app canvas.
- **Level 1 (Card / Resting):** Background `#FFFFFF`, Border `1px solid #E2E8F0`, Shadow: `0 2px 8px -2px rgba(15, 41, 66, 0.05), 0 1px 4px -1px rgba(15, 41, 66, 0.03)`.
- **Level 2 (Interactive Floating / Active Filter):** Background `#FFFFFF`, Shadow: `0 8px 18px -4px rgba(15, 41, 66, 0.08), 0 3px 6px -2px rgba(15, 41, 66, 0.04)`.
- **Level 3 (Modal / Sticky Consultation Drawer):** Background `#FFFFFF`, Border-top `1px solid #E2E8F0`, Shadow: `0 -4px 24px 0 rgba(15, 41, 66, 0.12)`.

Elevations incorporate a 1px border perimeter tinted with slate to ensure visible layer separation regardless of screen brightness or panel calibration.

## Shapes

The geometric vocabulary balances approachable consumer empathy with professional discipline using Level 2 roundedness:

- **Cards & Containers:** `16px` (`rounded-lg`) corner radius softening financial tables and plan cards.
- **Inputs & Action Buttons:** `12px` corner radius creating a confident, finger-friendly contour.
- **Badges & Trust Pills:** Full pill contour (`9999px`) to create an instant visual distinction between informative metadata and actionable rectangular cards.
- **Icon Enclosures:** Rounded squares (`10px` to `12px`) with light teal or amber background washes.

## Components

### Buttons
- **Primary CTA ("ปรึกษาคิมทันที / ขอใบเสนอราคา"):** Background `#F59E0B` (Amber), text `#0F2942` (Deep Navy for maximum contrast), semi-bold weight, min-height 48px, rounded 12px. Active press scales down slightly (`0.98`) with ambient amber glow.
- **Secondary CTA ("ดูรายละเอียดความคุ้มครอง"):** Transparent surface, border `1.5px solid #0F2942`, text `#0F2942`, min-height 48px.
- **Tertiary Utility ("ติดต่อผ่าน LINE"):** Background `#0D9488`, text `#FFFFFF`, rounded 12px, paired with LINE chat indicator.

### Badges & Status Chips
- **"แนะนำ" (Recommended):** Pill shape, amber background `#FEF3C7`, text `#B45309`, border `1px solid #FDE68A`.
- **"คุ้มครองทันที" (Active Cover):** Pill shape, teal background `#CCFBF1`, text `#0F766E`, border `1px solid #99F6E4`.
- **"เบี้ยประกันคงที่" (Fixed Premium):** Pill shape, slate background `#F1F5F9`, text `#334155`.

### Insurance Plan Comparison Cards
- Border `1px solid #E2E8F0`, interior padding `20px`.
- Card Header: Coverage title in `#0F2942` (Headline-sm), subtitle in `#475569`, accompanied by carrier or plan badge.
- Main Metric Block: Annual or monthly cost displayed prominently in Display-lg mobile (`#0F2942`) with subtext "เฉลี่ยวันละ ฿XX".
- Highlight Grid: 2–3 key coverage benefits accompanied by `#0D9488` teal checkmark circles (`18px`).
- Footer: Full-width conversion button.

### Form Inputs & Selectors
- Standard text input height `52px` with floating labels. Border `1px solid #CBD5E1`, focused state transitions to `#0D9488` with `0 0 0 3px rgba(13, 148, 136, 0.15)`.
- Segmented sliders for age/budget filters: Teal active thumb, slate track, bold price bubble anchored above the thumb.

### Sticky Mobile Consultation Bar
- Anchored at bottom viewport: height `76px` including iOS bottom safe indicator.
- Contains two elements: Left side displays Kim's agent thumbnail (`40px` circular) with "พร้อมให้คำแนะนำ" online indicator dot (`#10B981`); right side hosts the direct call/LINE CTA button.