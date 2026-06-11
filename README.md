# TRN MT1 Neutralization EQ Guide
## TRN MT1 + JCALLY JM6 + Equalizer APO + Viper4Windows

---

## Quick Start

If you want the fastest path to a usable setup:

1. Start with the profiles in the Parametric folder for the simplest Equalizer APO setup.
2. If you want a more natural tuning curve, try the AutoEQ folder next.
3. Use the FixedBand versions if you prefer a more traditional band-by-band EQ approach.
4. Only use the Convolution folder if your software supports WAV convolution loading.

### Folder Layout

- AutoEQ — ready-to-use EQ curves for a smoother overall response
- FixedBand — fixed-band EQ settings for manual tuning
- Parametric — standard parametric filter profiles for Equalizer APO
- Convolution — optional WAV-based tuning files for convolution processors

---

## Overview

This guide is based on a community-created TRN MT1 neutralization EQ project.

The TRN MT1 is often described as:

- Shouty in upper mids
- Slightly congested
- Mid-bass bleed
- Fatiguing at high volume

These EQ profiles aim to:

- Reduce harshness (2–5 kHz region)
- Improve soundstage perception
- Improve vocal balance
- Reduce listening fatigue
- Make MT1 more neutral and usable

---

## Hardware Setup

```text
TRN MT1
↓
JCALLY JM6 DAC
↓
Windows Laptop
↓
Equalizer APO
↓
Viper4Windows (optional)
↓
Music Player
```

---

# How to Apply the Profiles

## 1) Equalizer APO (Recommended)

The fastest setup is to use the Parametric or FixedBand files in Equalizer APO.

### Configuration File Location

You can directly apply EQ using copy-paste:

```text
C:\Program Files\EqualizerAPO\config\config.txt
```

### Method (Copy–Paste Technique)

1. Open the file above using Notepad (Run as Administrator if needed)
2. Copy the EQ profile you want (EQ001–EQ006)
3. Paste it inside `config.txt`
4. Save the file
5. Restart audio or reboot system

---

## 2) GUI Method

Use Equalizer APO Configuration Editor:

- Open the configuration editor
- Add a Preamp value if your profile includes one
- Add Parametric Filters
- Enter the values manually from the selected profile

## 3) Convolution (Optional)

If your player or DSP supports convolution:

```text
MT1_EQ00X_Convolution.wav
```

Use:

- Control → Convolution → Load WAV

This gives the most accurate representation of tuning.

---

# EQ Profiles Overview

Use this table as a quick starting point before opening a profile file.

| Profile | Character | Best For |
|----------|----------|----------|
| EQ001 | Mid-bass control | Rock, general use |
| EQ002 | Sub-bass heavy | EDM, Hip-Hop |
| EQ003 | Lean & detailed | Analytical listening |
| EQ004 | Balanced warm | Daily use |
| EQ005 | Open mids | Vocals |
| EQ006 | Neutral reference | Critical listening |

### Recommended Starting Point

- Start with EQ004 if you want the safest all-around tuning.
- Try EQ005 if you prefer more open vocals and a brighter presentation.
- Use EQ006 for a more neutral reference-style balance.

---

# Community Feedback (Original Post Comments)

From the original Facebook discussion:

> Neil Niño Clark
> bruh i gave my mt1 to my brothers..😅

> Niji James Jacobb Villagonzalo
> try this

> Harj Valencia
> Will try when i get home😁

> Bryan Yeo
> Can you try moondrop quarks next?

> Hi Fri
> Same. I wasn't a fan of their stock tonality... felt like I was going against the grain

> Fernando Aguila G
> #4 really makes them sing, thanks!

> Ivan Saha
> can u do kbear lark plz?

> Yinkong Yinkongsiento
> Think I prefer #3, looks more Harmanish 😂

---

# EQ001
## Reduced Mid-Bass Bleed

```ini
Preamp: -2.9 dB
Filter: ON PK Fc 766 Hz Gain 2.7 dB Q 0.81
Filter: ON PK Fc 2479 Hz Gain -6.9 dB Q 2.38
Filter: ON PK Fc 4418 Hz Gain -9.1 dB Q 3.12
Filter: ON PK Fc 5496 Hz Gain 2.3 dB Q 2.28
Filter: ON PK Fc 11785 Hz Gain 2.4 dB Q 0.17
Filter: ON PK Fc 76 Hz Gain -1.2 dB Q 0.48
Filter: ON PK Fc 408 Hz Gain 0.5 dB Q 1.83
```

---

# EQ002
## Sub-Bass Focused

```ini
Preamp: -3.5 dB
Filter: ON PK Fc 14 Hz Gain 3.6 dB Q 0.45
Filter: ON PK Fc 134 Hz Gain -5.3 dB Q 0.67
Filter: ON PK Fc 2478 Hz Gain -8.2 dB Q 1.86
Filter: ON PK Fc 3538 Hz Gain 3.7 dB Q 0.05
Filter: ON PK Fc 4357 Hz Gain -8.6 dB Q 3.92
Filter: ON PK Fc 4795 Hz Gain -1.0 dB Q 5.48
Filter: ON PK Fc 5592 Hz Gain 1.6 dB Q 3.94
Filter: ON PK Fc 6468 Hz Gain -0.3 dB Q 2.58
Filter: ON PK Fc 13528 Hz Gain -0.4 dB Q 1.26
```

---

# EQ003
## Less Warmth / Detailed

```ini
Preamp: -3.2 dB
Filter: ON PK Fc 731 Hz Gain 2.3 dB Q 1.10
Filter: ON PK Fc 2485 Hz Gain -7.5 dB Q 2.21
Filter: ON PK Fc 4423 Hz Gain -9.4 dB Q 3.06
Filter: ON PK Fc 5445 Hz Gain 2.4 dB Q 2.45
Filter: ON PK Fc 9461 Hz Gain 2.7 dB Q 0.10
Filter: ON PK Fc 81 Hz Gain -0.4 dB Q 0.91
Filter: ON PK Fc 165 Hz Gain -1.4 dB Q 1.02
Filter: ON PK Fc 414 Hz Gain 0.7 dB Q 2.05
Filter: ON PK Fc 2058 Hz Gain -0.2 dB Q 2.97
```

---

# EQ004
## Balanced With Warmth (Recommended Daily)

```ini
Preamp: -2.5 dB
Filter: ON PK Fc 41 Hz Gain -2.6 dB Q 0.36
Filter: ON PK Fc 487 Hz Gain 2.2 dB Q 0.43
Filter: ON PK Fc 2481 Hz Gain -8.0 dB Q 1.89
Filter: ON PK Fc 4353 Hz Gain -8.6 dB Q 3.88
Filter: ON PK Fc 7713 Hz Gain 2.5 dB Q 0.16
Filter: ON PK Fc 5752 Hz Gain 1.2 dB Q 4.98
Filter: ON PK Fc 8489 Hz Gain -0.2 dB Q 0.36
```

---

# EQ005
## Open Mids / Vocal Focus

```ini
Preamp: -3.2 dB
Filter: ON PK Fc 98 Hz Gain -4.9 dB Q 0.37
Filter: ON PK Fc 474 Hz Gain 3.5 dB Q 0.40
Filter: ON PK Fc 2480 Hz Gain -8.0 dB Q 1.90
Filter: ON PK Fc 4349 Hz Gain -8.4 dB Q 3.91
Filter: ON PK Fc 9376 Hz Gain 3.3 dB Q 0.12
Filter: ON PK Fc 2206 Hz Gain 0.1 dB Q 1.29
Filter: ON PK Fc 5759 Hz Gain 1.3 dB Q 5.16
Filter: ON PK Fc 7977 Hz Gain -0.2 dB Q 0.22
```

---

# EQ006
## Neutral Reference

```ini
Preamp: -3.7 dB
Filter: ON PK Fc 16 Hz Gain -4.9 dB Q 0.33
Filter: ON PK Fc 91 Hz Gain -2.6 dB Q 0.35
Filter: ON PK Fc 1282 Hz Gain 4.4 dB Q 0.14
Filter: ON PK Fc 2505 Hz Gain -10.3 dB Q 1.72
Filter: ON PK Fc 4364 Hz Gain -9.6 dB Q 3.10
Filter: ON PK Fc 1498 Hz Gain 0.3 dB Q 4.59
Filter: ON PK Fc 4958 Hz Gain -0.7 dB Q 2.91
Filter: ON PK Fc 5548 Hz Gain 1.6 dB Q 4.10
Filter: ON PK Fc 6867 Hz Gain -0.8 dB Q 3.01
Filter: ON PK Fc 17629 Hz Gain 0.6 dB Q 0.60
```

---

# Final Recommendation

For TRN MT1 users, the most practical order is:

1. Start with **EQ004** for daily listening
2. Compare with **EQ005** if you want more vocal openness
3. Try **EQ006** for a more neutral reference sound

Most users prefer:
- EQ004 → balanced, easy daily use
- EQ006 → reference/neutral tuning
