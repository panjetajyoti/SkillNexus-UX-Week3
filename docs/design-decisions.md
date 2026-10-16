# Design Decisions & System Documentation

## 1. Design Principles
- **Simplicity First:** Remove unnecessary visual noise; prioritize functionality over excessive decoration.
- **Progressive Disclosure:** Surface only the most critical information upfront, offering deeper context on demand.
- **Accessibility (WCAG 2.1 AA):** High contrast ratios and readable font sizing across both mobile and desktop screens.

---

## 2. Typography Scale
- **Display / Hero Titles:** 32px – 40px (Bold)
- **Section Headers (H1/H2):** 20px – 24px (Semi-Bold)
- **Body Text:** 14px – 16px (Regular, Line height: 1.5)
- **Captions & Metadata:** 12px (Medium)

---

## 3. Color System & Usage
- **Primary Color:** High-contrast accent for primary buttons, active tabs, and interactive states.
- **Neutral Dark:** Charcoal / Off-black for crisp, legible body typography without harsh eye strain.
- **Neutral Light:** Soft grays and clean whites for cards and clean background separation.
- **System States:**
  - Green: Success / Confirmation
  - Amber: In-progress / Warnings
  - Red: Error states and destructive actions

---

## 4. Usability & Layout Heuristics
- **Touch Targets:** Minimum 44x44px touch areas for mobile interactive controls.
- **Grid Structure:** 8pt grid system used consistently across padding, margins, and component spacing.
- **Feedback Loops:** Instant skeleton loaders and toast notifications to confirm user actions.
