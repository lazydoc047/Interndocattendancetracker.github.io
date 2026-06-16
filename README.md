# 📋 Internship Attendance Tracker

A fully offline, privacy-first attendance tracking web app for medical interns. No accounts, no servers, no hidden costs – **your data stays on your device**.

🔗 **Live Demo:** [https://lazydoc047.github.io/Interndocattendancetracker.github.io/](https://lazydoc047.github.io/Interndocattendancetracker.github.io/)

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| ⏱️ **Smart Attendance** | Full Day: Check‑in 8:45‑9:05 AM + Check‑out 12:30‑12:45 PM. Half Day: any other combination. Absent: no check‑in → auto‑deduct 1 leave. |
| 📅 **15 Leaves / Year** | Half day = 0.5 leave, Full day absent = 1 leave. Go beyond 15? Enter the Danger Zone! 😈 |
| 🔥 **Streak Counter** | Motivational messages for 3, 5, 7, 14, 30+ consecutive check‑ins. |
| 📖 **Daily Learning Log** | What did you learn today? Auto‑saved with each day's record. |
| 🩺 **Referral Tracker** | Log IPD No., Patient Name, Department (30+ with emojis), Referral Status (Pending, Accepted, Rejected, etc.), and mark "Referral Done". |
| ⭐ **Daily 5‑Star Rating** | Rate your day – tracks your mood and satisfaction. |
| 📝 **Editable Remarks** | Add custom notes to any day's record. |
| 📊 **Interactive Charts** | Bar chart (daily attendance), Pie chart (Full vs Half days), Cumulative trend line. Date range selector (7/15/30/180 days + custom). |
| 📸 **Photo Check‑In** | Take a selfie/photo as proof of attendance (stored locally). |
| 📜 **PDF Certificate** | Generate a beautiful attendance certificate with your name and percentage. |
| 🌙 **Dark Mode** | Easy on the eyes during night shifts. |
| 📁 **CSV Import/Export** | Full control over your data – backup & restore. |
| 🎉 **Holiday Calendar** | 2026 national & festival holidays – no leave deduction. |
| 🔔 **Push Notifications** | Daily reminders at 8:40 AM & 12:25 PM (browser notifications). |
| 🧪 **Admin Test Mode** | Password‑protected time/date simulation for testing rules. |
| 💬 **Daily Motivational Quotes** | Rotating quotes from Hippocrates, William Osler, Marcus Aurelius, and other great physicians & Stoics. |
| 🔒 **Privacy First** | All data stored locally in your browser (localStorage). No servers, no accounts, no tracking. |

---

## 📱 How to Use

### One‑Time Setup (30 seconds)

1. **Open the link** on any device:  
   `https://lazydoc047.github.io/Interndocattendancetracker.github.io/`

2. **Enter your name** and set your internship start date (optional).

3. **Allow notifications** when prompted (for daily reminders at 8:40 AM & 12:25 PM).

> 💡 *iPhone users:* After opening in Safari, tap **Share** → **"Add to Home Screen"** to get an app icon.

### Daily Workflow

1. **Check In** – any time (status will be classified based on timing).
2. **Log Learning** – type what you learned today.
3. **Add Referrals** – IPD, Patient, Department, Status.
4. **Rate Your Day** – tap ⭐ stars.
5. **Add Remarks** – optional notes.
6. **Check Out** – any time (status finalized after both timings).

### Attendance Classification

| Scenario | Status | Leave Deduction |
|----------|--------|-----------------|
| Check‑in 8:45‑9:05 **AND** Check‑out 12:30‑12:45 | ✅ Full Day | 0 |
| Any other timing combination | ⚠️ Half Day | 0.5 |
| No check‑in at all | ❌ Absent | 1 (auto‑deducted) |

> **Holidays:** No leave deduction on listed national & festival holidays.

---

## 🧪 Admin Test Mode

- Click the **🔐** button (bottom‑right).
- Enter password: **`admin123`**
- Enable test mode to simulate any time/date – perfect for testing rules without waiting.

---

## 🛠️ For Developers (Self‑Host)

```bash
# Clone the repository
git clone https://github.com/lazydoc047/Interndocattendancetracker.github.io.git

# Open index.html in any browser
# No build steps, no dependencies – just works!
