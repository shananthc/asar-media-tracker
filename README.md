# ASAR Media — Content Production Tracker

A complete, standalone internal operational dashboard and content production tracking platform custom-branded for **ASAR Media**.

---

## 🌟 Overview

This is a local, persistent operational dashboard tailored specifically for **ASAR Media** across its **Digital Marketing** and **Web Development** client operations.

### Team Roles & Structure:
- 👑 **Director & Founder (Owner)**: `SHAMITH`
- 👥 **Team Members (Employees)**:
  1. `SHAMI` — Production Specialist (Video Shoot, Production, Delivery)
  2. `RINISHA` — Video Editor (Video Editing, Reels & Cuts, Post-Production)
  3. `ASHMIJA` — Visual Designer (Graphic Design, Posters & Stories, Creatives)
  4. `JENOLOVIN` — Publishing Specialist (Delivery, Social Media Publishing, Scheduling)

---

## 🔐 Dual-Role Access & Identity Locking

### 1. Director View (Owner SHAMITH)
- **Privileges**: Full access to `👑 Owner`, `Setup`, `Finance`, `Dashboard`, and `✉ Invite Team`.
- **Passcode**: If opening on a new device, Director SHAMITH can unlock full access using PIN `1234` (or `2026`).
- **Live Preview Mode**: Test what each employee sees with 1 click using the **✉ Invite Team** → **Preview View** dropdown. An amber top bar lets the Director exit preview mode and return to Owner view anytime.

### 2. Employee View (SHAMI, RINISHA, ASHMIJA, JENOLOVIN)
- **First-Time Entry**: When employees open the tracker for the first time or via the invitation link (`?invite=team`), an onboarding modal prompts them to select their name.
- **Permanent Device Lock**: Once an employee selects and confirms their name, this browser/device is **permanently locked** to their identity:
  - Switching to another employee profile is strictly blocked.
  - The `👑 Owner` tab, `Setup` button, and administrative settings are completely hidden.
  - They only see their assigned work and can only log deliverables for their assigned role.

### 3. Automated Dates & Timestamps (Tamper-Proof)
- **Automatic Date**: Attendance marking is strictly locked to **Today's live date**. Employees cannot backdate or future-date attendance.
- **Automatic Live Clock-In**: Clock-in time is automatically captured from the live clock (`HH:MM`) when clicking "Present" or "Sign in". There is no manual input field to falsify entry time.
- **Automatic Live Clock-Out**: Clock-out time is automatically captured from the live clock when clicking "Leaving office · Sign out".
- **Live Breaks**: Tea, Lunch, and On-Duty departures automatically record exact departure and resumption minutes.

---

## ✉ How to Invite Employees

1. In the top-right header, Director SHAMITH clicks **✉ Invite Team**.
2. Choose your preferred distribution method:
   - **📋 Copy Invitation Link**: Share `[Tracker URL]?invite=team` directly.
   - **💬 1-Click WhatsApp Message**: Copies a ready-to-send WhatsApp invite formatted with emojis and step-by-step instructions.
   - **📧 1-Click Email Template**: Copies an email draft with subject line and clear guidelines.
3. When employees open the link, they tap their name once, tap confirm, and their device is ready!

---

## 🔄 Device Reset / Troubleshooting

If an employee changes their phone, laptop, or accidentally selected the wrong name:
- Open the tracker with `?reset_identity=1` appended to the URL.
- Or Director SHAMITH can open the **✉ Invite Team** modal on that computer and tap **Reset Identity on This Device**.

---

## 🚀 How to Run

Because this app features a self-contained local persistence engine, it runs **100% offline** in any browser with **zero dependencies**.

### Direct File Opening:
Double-click [`index.html`](file:///Users/shamith/Documents/asar-media-production-tracker%202/index.html) or run in Terminal:
```bash
open "/Users/shamith/Documents/asar-media-production-tracker 2/index.html"
```

### Local HTTP Server (Optional):
```bash
cd "/Users/shamith/Documents/asar-media-production-tracker 2"
python3 -m http.server 3000
```
Then visit `http://localhost:3000`.
