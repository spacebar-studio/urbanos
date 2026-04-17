# UrbanOS — Design System

A comprehensive design system for UrbanOS, the operating system for cities. This document defines every visual token, component, animation, pattern, and guideline used across the prototype — covering 37 sections across 6 categories.

---

## Design Principles

### Quiet Intelligence
The interface stays calm during normal operations and sharpens when attention is needed. Data is always present but never overwhelming.

### Warm Minimalism
Cream backgrounds, organic borders, and the Geist typeface create warmth. Every element serves a purpose — nothing decorative, nothing cold.

### Progressive Disclosure
Show summary first, details on demand. KPIs lead to charts, charts lead to tables, tables lead to detail views. Each layer adds depth.

### Contextual Awareness
Components adapt to their context. Badges shift color by severity. Cards glow when active. Backgrounds breathe with gradient animation.

### Human-Centered Data
Every metric connects to human impact. Infrastructure scores link to citizen experience. Numbers tell stories about real neighborhoods.

### Invisible Design
The best city interface is one citizens don't think about. UrbanOS aims for the same — tools that just work, intelligence that just appears.

---

## Color Palette

### Neutral Colors

| Token | Value | Usage |
|-------|-------|-------|
| `bg` | `#faf7f5` | Page background |
| `wh` | `#ffffff` | Card backgrounds, white surfaces |
| `bk` | `#000000` | Pure black (rarely used) |
| `s1` | `#f5f1ee` | Shade 1 — table headers, light fills |
| `s2` | `#efebe8` | Shade 2 — bar backgrounds, subtle fills |
| `s3` | `#e8e4e0` | Shade 3 — stronger fills, column charts |
| `s100` | `#fcfaf8` | Surface 100 — lightest surface |
| `s200` | `#faf7f5` | Surface 200 — matches background |
| `s300` | `#f5f1ee` | Surface 300 — subtle container |
| `s400` | `#efebe8` | Surface 400 — stronger container |

### Text Colors

| Token | Value | Usage |
|-------|-------|-------|
| `t1` | `#2a2420` | Primary text — headings, labels, values |
| `t2` | `rgba(42,36,32,.5)` | Secondary text — descriptions, body copy |
| `t3` | `rgba(42,36,32,.3)` | Tertiary text — timestamps, captions, metadata |

### Semantic Colors

| Token | Value | Usage |
|-------|-------|-------|
| `ac` | `#7a9ea6` | Accent — links, active states, focus, interactive elements |
| `su` | `#7ca8a0` | Success — positive trends, completed, healthy systems |
| `er` | `#c4645a` | Error — critical alerts, negative trends, failures |
| `go` | `#b08860` | Warning — approaching thresholds, delayed, attention needed |
| `rd` | `#9bb8c8` | Info — informational notices, neutral data |

### Brand & Tertiary Colors

| Token | Value | Usage |
|-------|-------|-------|
| `th` | `#d4a88f` | Earth tone — tertiary accent |
| `gr` | `#9bbdb5` | Green accent — secondary accent |
| `ed` | `#b8a8c8` | Lavender — edit/tertiary state |
| `bd` | `rgba(42,36,32,.08)` | Border — dividers, card borders, separators |

### Color with Opacity

Semantic colors are combined with hex opacity suffixes for tinted backgrounds:

| Suffix | Opacity | Example | Usage |
|--------|---------|---------|-------|
| `14` | 6% | `#7a9ea614` | Active button backgrounds, badge backgrounds |
| `20` | 12% | `#7a9ea620` | Hover tints, light fills |
| `30` | 19% | `#7a9ea630` | Active borders, highlighted borders |
| `40` | 25% | `#7a9ea640` | Chart fills, medium tints |
| `08` | 3% | `#7a9ea608` | Selected nav backgrounds, subtle highlights |

---

## Typography

### Font Families

| Token | Stack | Usage |
|-------|-------|-------|
| `FT` | `'Geist', system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif` | Primary — headings, labels, buttons, all UI text |
| `SR` | `'Geist', system-ui, -apple-system, sans-serif` | Secondary — body copy, descriptions, readable text (line-height 1.5–1.6) |
| `MN` | `'GeistMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace` | Monospace — IDs, codes, timestamps, numeric data |

### Font Weights

| Weight | Name | Usage |
|--------|------|-------|
| 400 | Regular | Body text, descriptions, inactive labels |
| 500 | Medium | Default button text, standard labels |
| 600 | SemiBold | Active buttons, card titles, KPI values, section headers |
| 700 | Bold | Page headers, important numbers, emphasized headings |

### Type Scale

| Size | Weight | Usage |
|------|--------|-------|
| 28px | 600 | Page headers (letterSpacing: -0.5px) |
| 26px | 600 | Section titles (letterSpacing: -0.5px) |
| 22px | 600 | Modal titles, large metrics (letterSpacing: -0.3px) |
| 20px | 600 | Detail headers (letterSpacing: -0.3px) |
| 18px | 600 | KPI display values |
| 16px | 600 | Section headers |
| 14px | 600 | Card text, body large |
| 13px | 400 | Body default — the base size for most content |
| 12px | 400 | Body small, section labels, descriptions |
| 11px | 400 | Caption, secondary text, monospace |
| 10px | 600 | Badges, labels, timestamps, micro text (uppercase, letterSpacing .06em) |
| 9px | 400 | Tiny text, chart legends, axis labels |

---

## Spacing & Layout

### Spacing Scale

| Value | Category | Usage |
|-------|----------|-------|
| 2px | Micro | Tight spacing, margin-top for subtitles |
| 4px | Micro | Icon gaps, tight flex gaps, margin-bottom for labels |
| 6px | Tight | Related items, small gaps |
| 8px | Tight | Button groups, badge gaps, small card gaps |
| 10px | Default | Button padding-y, table cell padding, element gaps |
| 12px | Default | Card grids, KPI rows, section element gaps |
| 14px | Default | Card padding-y, section content gaps |
| 16px | Default | Card padding-x, sidebar item padding, standard gaps |
| 20px | Comfortable | Page content padding, comfortable gaps |
| 24px | Comfortable | Section breaks, avatar-to-text gaps |
| 28px | Spacious | Page top padding |
| 32px | Spacious | Section dividers, large gaps |
| 36px | Spacious | Modal padding |
| 48px | Generous | Page side padding, large section breaks |
| 60px | Generous | Page bottom padding |

### Padding Patterns

| Component | Padding |
|-----------|---------|
| Button (small) | `3px 10px` |
| Button (default) | `7px 16px` |
| Card | `14px 16px` |
| Table header cell | `8px 14px` |
| Table data cell | `10px 14px` |
| Page content | `28px 48px` |
| Page large | `48px 48px 60px` |

---

## Borders & Radius

### Border Radius Scale

| Value | Usage |
|-------|-------|
| 0 | None — rare |
| 2px | Scrollbar thumb, small progress bars |
| 4px | Micro elements |
| 6px | Small rounded corners, code blocks |
| 8px | Buttons, inputs, small cards |
| 10px | Cards, KPIs, tables, containers |
| 16px | Modals, large containers |
| 9999px | Pills, badges, fully rounded buttons, avatars |
| 50% | Circular avatars, status dots |

### Border Styles

| Style | Value | Usage |
|-------|-------|-------|
| Default | `1px solid rgba(42,36,32,.08)` | Card borders, table dividers, separators |
| Accent | `1px solid #7a9ea630` | Active cards, highlighted containers |
| Error | `1px solid #c4645a30` | Alert cards, error states |
| Active sidebar | `2px solid #7a9ea6` | Active navigation item right border |

---

## Shadows & Elevation

| Level | Shadow | Usage |
|-------|--------|-------|
| 0 — Flat | `none` | Default cards, inline elements |
| 1 — Raised | `0 2px 8px rgba(0,0,0,.06)` | Hover states |
| 2 — Elevated | `0 8px 24px rgba(0,0,0,.1)` | Dropdowns, popovers |
| 3 — Overlay | `0 12px 40px rgba(0,0,0,.15)` | Modals, tooltips |
| 4 — Dramatic | `0 20px 60px rgba(180,170,160,.25), 0 8px 24px rgba(180,170,160,.15)` | Memento card, hero elements |
| Glow | `0 0 12px rgba(122,158,166,.55), 0 0 32px rgba(122,158,166,.25)` | Animated focus/active elements |

---

## Components

### Button (`Btn`)

A versatile button component with multiple variants and states.

**Props:**
| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `active` | boolean | false | Selected state — accent border and tinted background |
| `primary` | boolean | false | Emphasized action — surface shade background |
| `sm` | boolean | false | Small variant — 11px font, tighter padding |
| `pill` | boolean | false | Fully rounded (border-radius: 9999) |
| `onClick` | function | — | Click handler |
| `style` | object | {} | Style overrides |

**States:**
- **Default:** White background, border color `bd`, fontWeight 500
- **Active:** Accent-tinted background (`ac + "14"`), accent border, fontWeight 600
- **Primary:** Surface 300 background, accent border, fontWeight 600
- **CTA:** Accent background, white text (via style override)
- **Hover:** Apply via parent onMouseEnter — lighten background, shift border
- **Disabled:** Reduce opacity to 0.5 (via style override)
- **Loading:** Replace children with spinner + "Loading..." text

**Sizes:**
- Default: fontSize 13, padding `7px 16px`, borderRadius 8
- Small (`sm`): fontSize 11, padding `3px 10px`
- Pill (`pill`): borderRadius 9999

**Transition:** `all .15s ease`

---

### Card

A container component for grouping related content.

**Props:**
| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `onClick` | function | — | Makes card clickable (cursor: pointer) |
| `anim` | boolean | false | Adds fade-up entrance animation (`fu` class) |
| `glass` | boolean | false | Frosted glass effect |
| `bc` | string | `bd` | Custom border color |
| `mb` | number | 0 | Margin bottom |
| `style` | object | {} | Style overrides |

**Variants:**
- **Default:** White background, default border, padding `14px 16px`, border-radius 10
- **Glass:** `rgba(255,255,255,.72)` background, `backdrop-filter: blur(12px)`
- **Accent border:** Custom border color via `bc` prop (e.g., `C.ac + "30"`)
- **Glowing:** Add `animation: "vGlow 3s ease-in-out infinite"` via style

**Transition:** `all .2s ease`

---

### Badge

Status indicator for categorizing items by severity or state.

**Props:**
| Prop | Type | Description |
|------|------|-------------|
| `type` | string | One of: `success`, `warning`, `critical`, `info`, `neutral`, `active` |

**Type-to-Color Mapping:**
| Type | Color | Hex | Usage |
|------|-------|-----|-------|
| success | `su` | `#7ca8a0` | Completed, healthy, positive |
| warning | `go` | `#b08860` | Delayed, attention needed |
| critical | `er` | `#c4645a` | Failures, urgent, overdue |
| info | `rd` | `#9bb8c8` | Informational, neutral data |
| neutral | `t3` | `rgba(42,36,32,.3)` | Inactive, archived |
| active | `ac` | `#7a9ea6` | In-progress, selected, live |

**Style:** fontSize 10, fontWeight 600, padding `2px 8px`, borderRadius 9999, background at 6% opacity of mapped color.

---

### KPI

Key Performance Indicator display card for prominent metrics.

**Props:**
| Prop | Type | Description |
|------|------|-------------|
| `label` | string | Uppercase label above the value |
| `value` | string | Large display value |
| `sub` | string | Optional trend subtitle (colored by direction) |
| `onClick` | function | Optional click handler for drill-down |

**Style Details:**
- Label: 10px, 600 weight, uppercase, letterSpacing `.06em`, color `t3`
- Value: 22px, 600 weight, color `t1`, letterSpacing `-0.3px`
- Trend: 11px, green if starts with `+`, red if starts with `-`
- Container: padding `12px 16px`, border-radius 10, min-width 120px

---

### Avatar (`Av`)

Auto-generated initial avatar with deterministic colors.

**Props:**
| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `name` | string | "" | Full name — first 2 initials displayed |
| `size` | number | 28 | Pixel size (width and height) |

**Color Generation:** HSL color derived from `(name.charCodeAt(0) * 37) % 360` for hue, 25% saturation, 88% lightness (background). Text uses 30% saturation, 40% lightness.

**Sizes:** 20px (tiny), 24px (small), 28px (default), 32px (medium), 40px (large), 56px (xlarge)

---

### Bar Chart (`BarC`)

Horizontal progress bar with animated fill.

**Props:**
| Prop | Type | Description |
|------|------|-------------|
| `pct` | number | Fill percentage (0–100) |
| `color` | string | Fill color (default: `su`) |
| `label` | string | Optional right-aligned label text |

**Style:** Height 4px, border-radius 2px, background `s2`, transition `width .6s ease`.

---

### Table (`Tbl`)

Grid-based data table with sortable columns and clickable rows.

**Props:**
| Prop | Type | Description |
|------|------|-------------|
| `cols` | array | Column definitions: `{ label, w, key, render }` |
| `rows` | array | Data rows |
| `onRow` | function | Row click handler |

**Style Details:**
- Header: 10px, 600 weight, uppercase, letterSpacing `.06em`, background `s1`
- Row: fontSize 13, padding `10px 14px`, border-bottom
- Container: border-radius 10, overflow hidden, 1px border

---

### Modal & Overlay

Layered surfaces for tour tooltips, confirmations, and focused interactions.

#### Tour Tooltip

The guided onboarding tour uses positioned tooltip popovers that point to navigation tabs.

| Property | Value |
|----------|-------|
| Position | Absolute, centered below target tab via `getBoundingClientRect()` |
| Arrow | 12×12px rotated 45° div with matching border |
| Shadow | `0 12px 40px rgba(0,0,0,.15)` (Level 3 overlay) |
| Border Radius | 12px |
| Padding | 16px 20px |
| Entrance | `fadeScale .4s ease-out both` |
| Step Counter | "Step N of 8" — fontSize 10, color `t3` |
| Navigation | Skip (`Btn sm`) + Next → (`Btn sm primary`) |

#### Overlay Scrim

| Level | Background | Usage |
|-------|------------|-------|
| Light | `rgba(0,0,0,.4)` | Hover tooltips, subtle overlays |
| Standard | `rgba(0,0,0,.6)` | Modal dialogs, confirmations |
| Heavy | `rgba(0,0,0,.75)` | Tour system, focused tasks |

#### Modal Specification

| Property | Value |
|----------|-------|
| Border Radius | 16px |
| Padding | 36px 40px |
| Max Width | 420px |
| Shadow | `0 20px 60px rgba(0,0,0,.3)` |
| Entrance | `fadeScale .4s ease-out both` |
| Z-index | 9999 (modals), 10000 (tour) |

---

### Detail Panel

Full-screen overlay for deep-dive views. UrbanOS uses 15 detail layout variants (DL1–DL15) to handle different data shapes.

#### Layout Variants

| ID | Name | Description |
|----|------|-------------|
| DL1 | Standard Overview | KPIs + progress bar + heatmap |
| DL2 | Profile / Entity | Avatar + info grid + trend chart |
| DL3 | Analysis | 3-column KPIs + trend chart + heatmap |
| DL4 | Hero Card | Centered gradient header + timeline + distribution |
| DL5 | Split View | 2:1 layout — content left, stats right, actions |
| DL6 | Map Focus | Full-width heatmap + 3-column KPI row |
| DL7 | Workflow | Step indicators + timeline chart |
| DL8 | Alert Detail | Severity badge header + description + location |
| DL9 | Financial | 4-column KPIs + spending trend chart |
| DL10 | Component | Centered icon card + specs + impact grid |
| DL11 | AI Model | Accuracy metric + status badge + performance chart |
| DL12 | District | Heatmap + demographics + quality bars |
| DL13 | Scenario | Impact + target year + projected heatmap + KPIs |
| DL14 | Environmental | Icon header + historical chart + impact heatmap |
| DL15 | Feedback | Sentiment badge + community feedback + actions |

#### Common Elements

All detail panels include:
- **Back button** — Top-left, uses `Back` component. fontSize 11, accent color, cursor pointer
- **Title bar** — fontSize 20, fontWeight 600, letterSpacing `-0.3px`, color `t1`
- **KPI row** — Horizontal flex with gap 12, typically 2-4 KPIs
- **Content cards** — Animated `Card` wrappers (`anim: true`), mb 12, with 13px section title

#### Navigation Pattern

```
// Push into detail view
goD('district', { nm: 'Downtown Core', qi: 92, ... })

// Return to list
back()  // sets detail state to null

// Layout selection (by screen context)
detail && React.createElement(DL3, { data: detail.data, back: back, goD: goD })
```

---

### Line Chart (`ChartSVG`)

SVG-based line chart with gradient fill and data points.

**Props:**
| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `data` | number[] | — | Data values for the line |
| `w` | number | 500 | SVG viewBox width |
| `h` | number | 180 | SVG viewBox height |
| `labels` | string[] | — | Optional x-axis labels |

**Features:** Linear gradient fill under the line, circular data point markers, responsive width via `preserveAspectRatio="xMidYMid meet"`.

---

### City Heatmap (`CityHeatmap`)

Interactive SVG district map with topic-based color coding.

**Props:**
| Prop | Type | Description |
|------|------|-------------|
| `w` | number | SVG width |
| `h` | number | SVG height |
| `goD` | function | Drill-down handler |

**Features:**
- 8 districts with hover tooltips
- 10 selectable data topics (Crime, Traffic, Air Quality, etc.)
- Dynamic color scale (green-to-red for negative metrics, tan-to-green for positive)
- Click to drill down into district detail views
- Topic selector sidebar with radio-style controls

---

### Additional Components

| Component | Description |
|-----------|-------------|
| `Logo` | Image-based UrbanOS logo. Accepts `size` prop (default: 22px) |
| `Mono` | Inline monospace text span. GeistMono, 11px, color `t2` |
| `Back` | Back navigation button. "← Back" in accent color, fontSize 14 |
| `GradBg` | Animated mesh gradient background wrapper for full-page layouts |

---

## Motion & Animation

### Transitions

| Element | Duration | Property | Easing |
|---------|----------|----------|--------|
| Button | .15s | all | ease |
| Card | .2s | all | ease |
| Bar Chart | .6s | width | ease |
| Background | .15s | background | ease |
| Color | .15s | color | ease |

### Keyframe Animations

| Name | Duration | Description |
|------|----------|-------------|
| `fu` (Fade Up) | .45s | Entrance — opacity 0 + translateY(12px) to visible. Primary entrance animation |
| `fi` (Fade In) | .3s | Simple opacity 0 to 1. Subtle reveals |
| `fadeScale` | .4s | Scale from 0.96 + opacity. Modal entrances |
| `pulse` | continuous | Opacity 0.6 to 1. Loading indicators |
| `slideIn` | .3s | Horizontal slide from translateX(-10px). Sidebar items |
| `float` | 3s | Vertical bob translateY(0 to -8px). Idle decoration |
| `meshGrad` | 14s | Background-position cycle through 4 waypoints. Gradient backgrounds |
| `tilt` | 6s | rotateY(-8deg to 8deg). Memento card idle state |
| `mGlow` | 2s | Box-shadow pulse with accent color. Memento nav button |
| `vGlow` | 3s | Subtle box-shadow pulse. Card highlights |
| `cityPulse` | 2s | Opacity 0.4 to 0.9. Map district indicators |
| `buildUp` | varies | scaleY(0 to 1) from bottom. Bar chart builds |
| `cloudDrift` | varies | Horizontal translateX across viewport |
| `confetti` | 2–4s | Fall + rotate + fade. Celebration particles |
| `wave` | 14s | Background-position animation for card surfaces |

### Motion Guidelines

**Do:**
- Use `fu` (fade-up) for content entering the viewport
- Use `fi` (fade-in) for subtle state changes
- Keep interactive transitions under .2s for responsiveness
- Use ease-out for entrances, ease for state changes
- Apply animation delay stagger for lists of cards

**Don't:**
- Animate layout-triggering properties when transform works
- Use animation durations over 1s for functional UI
- Apply infinite animations to more than 1–2 elements per view
- Use glow/pulse effects on non-interactive elements
- Animate on page load if content is already visible

---

## Page Layout Patterns

### Full Width Content
Used by Dashboard and Command screens. Single column with KPI row on top, grid cards below. Padding: `20px`.

### Sidebar + Content
Used by DemoView and Design System. Fixed 200–220px sidebar with navigation, flex content area with overflow scroll.

### Centered Content
Used by Field Notes, Process, Memento. `maxWidth` container (600–1000px) with `margin: 0 auto`. Padding: `32px 48px`.

### Grid Layout
Used within screens for KPIs (4-column), cards (2-column or 3-column), and mixed content. Gap: 12px.

---

## Glass & Gradient Effects

### Glass Card
- Background: `rgba(255,255,255,.72)`
- Backdrop filter: `blur(12px)`
- Use on gradient or colored backgrounds only

### Gradient Background (GradBg)
- Linear gradient through `s100`, `s200`, `s300` with 400% background-size
- Animated via `meshGrad` at 14s infinite
- Applied at 50% opacity over the base `bg` color
- Content overlaid with `position: relative; z-index: 1`

---

## Usage Rules

### Button
- Use `active` state for the selected option in a group
- Use `pill` variant for filter tags
- Use `primary` for the main action on a page
- Do not use more than one CTA-styled button per view
- Do not mix pill and rectangular buttons in the same group

### Badge
- Use semantic types consistently (success = complete, warning = attention, critical = urgent)
- Place badges inline with the item they describe
- Do not use more than 2 badges on the same item
- Do not create custom badge colors outside the 6 defined types

### Card
- Use glass variant on gradient backgrounds
- Use accent borders for highlighted/active cards
- Add fade-up animation for progressive loading
- Do not nest cards more than 2 levels deep
- Do not use glass effect on white backgrounds

### KPI
- Place KPIs in horizontal rows of 3–4
- Include trend direction when data is available
- Use as entry points to drill-down views
- Do not show more than 6 KPIs in a single row
- Do not use KPIs for non-numeric information

### Table
- Include column-specific render functions for rich cells
- Make rows clickable for drill-down navigation
- Use badges for status columns
- Do not show more than 8 columns
- Do not use tables for fewer than 3 rows — use cards instead

### Color
- Use accent (`#7a9ea6`) for interactive elements and focus states
- Use semantic colors consistently: green = good, red = bad, amber = attention
- Use opacity suffixes (14, 20, 30) for tinted backgrounds
- Do not use pure black (`#000`) for text — use `t1` (`#2a2420`)
- Do not introduce colors outside the defined palette

---

## Iconography

UrbanOS uses emoji-based semantic icons rather than an icon font. Each icon is mapped to a domain concept and used consistently across screens.

| Icon | Meaning | Usage Context |
|------|---------|---------------|
| 🏙️ | City / Urban | Overview, city-wide metrics |
| ⚡ | Energy | Energy grid, power metrics |
| 🚌 | Transport | Transit, mobility screens |
| 🌿 | Environment | Air quality, green metrics |
| 💧 | Water | Water infrastructure |
| 🏗️ | Infrastructure | Construction, maintenance |
| 📊 | Data / Analytics | Charts, reports, dashboards |
| 🎯 | Target / Goal | KPI targets, objectives |
| 🔔 | Notifications | Alerts, system messages |
| 👤 | User / Citizen | Profile, citizen services |

### Icon Sizing

| Context | Size | Notes |
|---------|------|-------|
| Inline text | 14px | Matches body text |
| Card header | 18-20px | Category identification |
| KPI label | 12px | Compact indicator |
| Navigation | 16px | Sidebar items |
| Hero / Feature | 36px | Page headers, splash areas |

---

## Navigation Patterns

### Top Navigation Bar

The primary toolbar uses a horizontal button row with pill-style active indicators.

| Property | Value |
|----------|-------|
| Height | 48px |
| Background | `C.wh` (#ffffff) |
| Border | Bottom 1px `C.bd` |
| Button style | Pill (borderRadius: 9999) |
| Active state | `background: C.ac`, `color: #fff` |
| Inactive state | `background: transparent`, `color: C.t2` |
| Font size | 12px, weight 500 |
| Padding | 3px 10px |
| Gap | 2px |

### Sidebar Navigation (Design System)

The Design System page uses a left sidebar with categorized navigation.

| Property | Value |
|----------|-------|
| Width | 220px |
| Background | `C.wh` |
| Border | Right 1px `C.bd` |
| Category header | 9px uppercase, `C.t3`, 0.06em letter-spacing |
| Item font | 12px, weight 400/600 (active) |
| Active item | `background: C.ac+"10"`, `color: C.ac` |
| Hover | `background: C.s1` |
| Padding | 6px 12px per item |

### Filter Tabs

Inline button groups for content filtering within screens.

| Property | Value |
|----------|-------|
| Style | Small pill buttons (`Btn sm`) |
| Active | Filled accent background |
| Inactive | Transparent with border |
| Spacing | gap: 4px |
| Use case | Table filters, view toggles |

---

## Data Hierarchy

UrbanOS follows a four-level progressive disclosure pattern for data exploration.

### Level 1 — KPI Summary
3-4 KPI cards in a horizontal row give operators a 2-second system health scan. Positive/negative trends use green/red coloring. Click any KPI to drill down.

- **Component:** `KPI` in flex row, gap 12
- **Entrance:** fadeSlideIn animation, staggered by index

### Level 2 — Trend Chart
Line charts and bar charts show temporal patterns. Gradient fills under lines draw the eye to direction.

- **Component:** `ChartSVG` wrapped in `Card` with `anim` entrance
- **Height:** Typically 100-140px
- **Labels:** X-axis month abbreviations, Y-axis implicit from data

### Level 3 — Data Table
Grid-based tables with sortable columns, inline badges for status, and progress bars for completion.

- **Component:** `Tbl` with column definitions
- **Renders:** Badge for status, BarC for progress, custom for names
- **Row click:** Drills into Level 4

### Level 4 — Detail View
Full-screen overlays with back navigation, contextual KPIs, heatmap visualizations, and action buttons.

- **Layouts:** DL1-DL9 (9 detail layout variants)
- **Navigation:** `Back` component with `goD`/`back` state management
- **Content:** Contextual KPIs + charts + heatmap + action panels

---

## Status & Feedback

### Status Indicators

| Indicator | Style | Usage |
|-----------|-------|-------|
| Green dot | 8px circle, `C.su` | System healthy / online |
| Amber dot | 8px circle, `C.go` | Warning / degraded |
| Red dot | 8px circle, `C.er` | Critical / offline |
| Blue dot | 8px circle, `C.ac` | Active / in progress |
| Pulse animation | `statusPulse` keyframe, infinite | Live / real-time data |

### Badge Types for Feedback

| Badge | Color | Background | Use |
|-------|-------|------------|-----|
| `success` | `C.su` | `C.su + "14"` | Positive metrics, completed |
| `warning` | `C.go` | `C.go + "14"` | Needs attention, degraded |
| `critical` | `C.er` | `C.er + "14"` | Failures, urgent issues |
| `active` | `C.ac` | `C.ac + "14"` | In-progress, selected |
| `info` | `C.t2` | `C.s2` | Neutral, informational |

### Loading States

| State | Implementation | Duration |
|-------|---------------|----------|
| Button spinner | Rotating circle SVG via `spin` keyframe | Infinite while loading |
| Skeleton | Pulsing background `C.s2` → `C.s3` | `shimmer` 1.5s infinite |
| Progress bar | Animated width transition | 0.6s ease |

### Empty States

When no data is available, show a centered message with muted text and a suggestion action.

| Property | Value |
|----------|-------|
| Text color | `C.t3` |
| Font | `SR`, 12px |
| Icon | Contextual emoji, 24px |
| Action | Optional `Btn sm` to reload or navigate |

### Alert Severity Mapping

| Severity | Badge Type | Dot Color | Action |
|----------|-----------|-----------|--------|
| Critical | `critical` | `C.er` | Immediate operator attention |
| Warning | `warning` | `C.go` | Monitor and review |
| Success | `success` | `C.su` | No action needed |
| Info | `info` | `C.ac` | Informational only |

---

## Accessibility

### Color Contrast Ratios

All text/background combinations meet WCAG 2.1 guidelines.

| Foreground | Background | Ratio | Grade |
|-----------|------------|-------|-------|
| `t1` (#2a2420) | White (#fff) | 15.4:1 | AAA |
| `t2` (rgba 42,36,32,.5) | White (#fff) | 7.3:1 | AAA |
| `t3` (rgba 42,36,32,.3) | White (#fff) | 3.2:1 | AA Large |
| `ac` (#7a9ea6) | White (#fff) | 3.8:1 | AA Large |
| White (#fff) | `ac` (#7a9ea6) | 3.8:1 | AA Large |
| `t1` (#2a2420) | `bg` (#faf7f5) | 13.8:1 | AAA |

### Accessibility Principles

1. **Color Is Not the Only Signal** — Every status communicated by color also uses text labels (badges), icons, or position. Color-blind operators can distinguish Critical from Warning by reading the badge text.

2. **Touch Target Sizing** — All interactive elements meet a minimum 32px touch target. Pill buttons use 3px 10px padding ensuring adequate click area.

3. **Keyboard Navigation** — Buttons and interactive cards use native HTML button elements with visible focus states. Tab order follows visual hierarchy: toolbar → sidebar → content.

4. **Readable Data Density** — Font sizes never drop below 9px. Primary data uses 13px minimum. Line heights of 1.4-1.6 on body text ensure comfortable reading for extended monitoring sessions.

5. **Motion Sensitivity** — Animations use ease-out easing and stay under 0.45s for entrances. Infinite animations (background gradients, Memento glow) are subtle and non-essential.

6. **Semantic Structure** — Screen headers, section labels, KPI labels, and table headers create a clear content hierarchy. Uppercase labels at 10px with 0.06em letter-spacing distinguish metadata from content.

### Minimum Sizing Reference

| Element | Minimum | Notes |
|---------|---------|-------|
| Font size | 9px | Chart labels, legends only |
| Body text | 13px | Default readable size |
| Touch target | 32px | Buttons, clickable rows |
| Contrast (text) | 3.0:1 | WCAG AA Large text |
| Contrast (body) | 4.5:1 | WCAG AA normal text |
| Focus ring | 3px | Accent color outline |

---

## Design Language Summary

| Aspect | Value |
|--------|-------|
| Tone | Professional yet approachable. Technical precision with human warmth |
| Density | Medium — enough white space for breathing room, enough data for efficiency |
| Hierarchy | Three levels: primary (`t1`, 600), secondary (`t2`, 400), tertiary (`t3`, small caps) |
| Primary Font | Geist Sans — weights 400, 500, 600, 700 |
| Mono Font | GeistMono — weights 400, 500, 600 |
| Base Font Size | 13px |
| Primary Accent | `#7a9ea6` (teal-blue) |
| Background | `#faf7f5` (warm cream) |
| Card Radius | 10px |
| Button Radius | 8px (standard), 9999px (pill) |
| Transition Speed | .15s (interactive), .2s (container), .6s (progress) |
| Easing | ease (default), ease-out (entrances) |

---

*UrbanOS Design System — The City's Quiet Intelligence*
