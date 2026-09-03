# 🤖 GIMI - MacroDroid Setup Guide

**Complete installation guide for GIMI on your Samsung phone using MacroDroid (FREE)**

---

## 📱 What You'll Do

1. Install MacroDroid (free)
2. Give it permissions
3. Import GIMI automation rules
4. Activate and obey

**Time needed:** 15 minutes  
**Cost:** $0  
**Mercy:** 0

---

## ✅ Step 1: Install MacroDroid

```
1. Open Google Play Store on your Samsung phone
2. Search: "MacroDroid - Device Automation"
3. Tap "Install" (FREE)
4. Wait for installation
5. Open MacroDroid
```

**You should see:** A screen with "Macros" and a "+" button to create new automations.

---

## ✅ Step 2: Give MacroDroid Permissions

**Device Admin (MOST IMPORTANT):**
```
Settings 
  → Apps 
  → MacroDroid 
  → Permissions
  → Device Admin Apps
  → Enable "MacroDroid"
```

**This lets MacroDroid:**
- Lock your screen
- Block app launches
- Control settings

**Other Permissions to Enable:**
```
Settings → Apps → MacroDroid → App Permissions:
✅ Camera (optional - for emergency detection)
✅ Phone (to detect calls)
✅ SMS (to detect texts)
✅ Storage (for logs)
✅ Location (optional)
✅ Health/Fitness (to read step count)
```

**Do NOT skip Device Admin** — GIMI needs this to lock you out at 10 PM.

---

## ✅ Step 3: Create GIMI Automation Rules

MacroDroid uses "Macros" = automation rules.

**You'll create these 5 macros:**

### **Macro 1: WAKE UP AT 6 AM (Forced Alarm)**

```
Macro Name: "GIMI - Morning Alarm"

TRIGGER:
  Time: 6:00 AM (every day)

ACTIONS:
  1. Start sound: Loud alarm (loudest available)
  2. Vibration: Continuous heavy vibration
  3. Display notification: "GET YOUR ASS OUT OF BED. NOW."
  4. Disable mute: Unmute phone (no silent mode)
  5. Brightness: Maximum (100%)
  6. Keep phone awake: Yes (screen stays on)

REPEAT: Every day at 6:00 AM
STATUS: Enabled ✓
```

**How to create in MacroDroid:**
```
1. Open MacroDroid
2. Tap "+" (add macro)
3. Tap "Trigger" → Select "Time"
4. Set time: 6:00 AM
5. Tap "Add Action"
6. Choose "Sound/Vibration" → Alarm
7. Add more actions (notification, brightness, etc.)
8. Save macro
```

---

### **Macro 2: BLOCK SOCIAL MEDIA (Morning - Evening)**

```
Macro Name: "GIMI - Block Social Media"

TRIGGER:
  Time: 6:00 AM (every day)

ACTIONS:
  1. Block apps until 8:00 PM:
     - TikTok
     - Instagram
     - Twitter/X
     - Snapchat
     - Discord
     - Facebook
     - Reddit
     - YouTube
     - WhatsApp (optional)
  2. Display notification: "Social media blocked. Earn your freedom with 8,000 steps."

REPEAT: Every day at 6:00 AM
DURATION: Until 8:00 PM
STATUS: Enabled ✓
```

**How to create in MacroDroid:**
```
1. Tap "+" (add macro)
2. Trigger: Time 6:00 AM
3. Action: "Block/Unblock Apps"
4. Select apps to block (check all social media)
5. Set block duration: Until 8:00 PM
6. Save macro
```

---

### **Macro 3: ALLOW 30 MIN FREE TIME (8:00 PM - 8:30 PM)**

```
Macro Name: "GIMI - Evening Freedom 30 Min"

TRIGGER:
  Time: 8:00 PM (every day)

ACTIONS:
  1. Unblock apps:
     - TikTok
     - Instagram
     - Twitter/X
     - Snapchat
     - Discord
     - Facebook
     - Reddit
     - YouTube
  2. Display notification: "30 MINUTES OF FREEDOM. Enjoy. Then locked again at 8:30 PM."
  3. Set timer: 30 minutes

REPEAT: Every day at 8:00 PM
STATUS: Enabled ✓
```

---

### **Macro 4: RE-BLOCK SOCIAL MEDIA (8:30 PM)**

```
Macro Name: "GIMI - Reblock at 8:30 PM"

TRIGGER:
  Time: 8:30 PM (every day)

ACTIONS:
  1. Block apps again:
     - TikTok
     - Instagram
     - Twitter/X
     - Snapchat
     - Discord
     - Facebook
     - Reddit
     - YouTube
  2. Display notification: "FREEDOM OVER. Prepare for sleep."
  3. Enable Do Not Disturb mode

REPEAT: Every day at 8:30 PM
STATUS: Enabled ✓
```

---

### **Macro 5: SLEEP LOCK (10:00 PM - 6:00 AM)**

```
Macro Name: "GIMI - Sleep Lock"

TRIGGER:
  Time: 10:00 PM (every day)

ACTIONS:
  1. Lock device (screen lock)
  2. Disable unlock methods:
     - Fingerprint: OFF
     - Face recognition: OFF
     - PIN/Password: Temporary disable
  3. Enable Do Not Disturb (no notifications)
  4. Enable Airplane mode (optional - stricter)
  5. Set screen brightness: 0% (black)
  6. Display message (lock screen): "SLEEP NOW. Locked until 6:00 AM."

REPEAT: Every day at 10:00 PM
DURATION: Until 6:00 AM
STATUS: Enabled ✓
```

**IMPORTANT:** This is the hardest lock. You CANNOT unlock until 6 AM (except real emergency).

---

### **Macro 6: MORNING UNLOCK (6:00 AM)**

```
Macro Name: "GIMI - Morning Unlock"

TRIGGER:
  Time: 6:00 AM (every day)

ACTIONS:
  1. Unlock device
  2. Enable fingerprint/face recognition
  3. Disable Airplane mode
  4. Disable Do Not Disturb
  5. Disable sleep lock
  6. Display notification: "GOOD MORNING. Get up and move."

REPEAT: Every day at 6:00 AM
STATUS: Enabled ✓
```

---

## ✅ Step 4: Link GIMI AI Brain (Optional but Recommended)

For the lie detector and emergency check:

### **Install Ollama (Free AI)**

```
1. Go to F-Droid app store (alternative to Google Play)
2. Search: "Ollama"
3. Install
4. Open Ollama
5. Download model: "mistral" (small, fast, free)
```

### **Create Emergency Override Macro**

```
Macro Name: "GIMI - Emergency Override Request"

TRIGGER:
  Volume button press (hold down during sleep lock)

ACTIONS:
  1. Display dialog: "What's the emergency? (reply)"
  2. Send your answer to Ollama AI
  3. AI decides: Truth or Lie?
  4. If TRUTH: Unlock for 15 minutes
  5. If LIE: Bedtime moves to 9 PM tomorrow

STATUS: Enabled ✓
```

---

## ✅ Step 5: Track Your Stats (Optional Dashboard)

Create a simple tracking sheet:

```
Daily Checklist:
□ Woke up at 6 AM
□ Hit 8,000+ steps
□ Obeyed all app blocks
□ No emergency overrides
□ Slept 8 hours
□ Rating: ___/10
```

**Save this in:** Notes app, Google Sheets, or simple text file

---

## ⚠️ CRITICAL: Cannot Undo Easily

Once you enable these macros:

```
❌ You CANNOT:
- Easily disable them (they lock you out)
- Uninstall MacroDroid (it needs admin)
- Bypass the 10 PM lock (it's absolute)
- Negotiate with GIMI

✅ You CAN:
- Disable MacroDroid in Device Admin (but GIMI will alert you)
- Use emergency override (if GIMI accepts)
- View your stats
- Wait for 6 AM unlock
```

**Are you SURE you want GIMI to have this much control?**

---

## 🚀 Ready to Activate?

```
1. All macros created? ✓
2. Device Admin enabled? ✓
3. Permissions granted? ✓
4. No mercy? ✓

THEN: Enable all macros and press START

GIMI is now in control.
```

---

## 📞 Emergency Override (If Needed)

**During sleep lock (10 PM - 6 AM):**

```
1. Hold Volume Down button
2. GIMI AI asks: "Emergency?"
3. You explain
4. AI analyzes: Truth or Lie?
5. If TRUTH → 15 min unlock
6. If LIE → Punishment tomorrow
```

**Real emergencies:**
- Medical emergency
- Family crisis
- Police/legal issue
- Someone in danger

**Fake emergencies (WILL be punished):**
- "Can't sleep"
- "Friend texted"
- "Just 5 minutes"
- Anything obvious

---

## ✅ Checklist Before Activation

- [ ] MacroDroid installed
- [ ] Device Admin enabled
- [ ] All 6 macros created
- [ ] Ollama installed (optional but recommended)
- [ ] Emergency override macro created
- [ ] Ready for NO MERCY mode

**When all checked:** Activate macros and obey GIMI.

🔒 **Let's go.**
