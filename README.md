# Hush — Pulses paywall, personalized from the onboarding

**Live page: https://plykhvar-glitch.github.io/hush-paywall-rebuild/**

Hush's Pulses paywall, rebuilt in its own design and personalized with what the onboarding already
asks: the name, who someone wants to talk to, and their mood (Friends, Intimate or Deep). Change the
answers under the phone and the paywall rewrites itself. Flip **Today** to see the version that
ships now. English and French, light and dark, plus a 30-second walkthrough.

## The five changes

| # | Change | Today | Now | Expected impact |
| :-- | :-- | :-- | :-- | :-- |
| 1 | Their name and who they want in the headline | "Increase your chances to get a match." for everyone | "Maya, be the like he answers." — she or they for Women or Everyone | CR +15–20% |
| 2 | A pulse arriving, signed with their name | "Add messages to your likes with pulses." and a paper plane | Your own notification card: "Maya liked you, with a message", with the send counter showing the selected pack | CR +10–15% |
| 3 | Your proof next to the price | "1M+ conv started" appears only in the onboarding | "1M+ conversations started" above the packs; 4.5 from 5.3K App Store ratings on the French screen | CR +10–15% |
| 4 | The mood they picked, on the screen | One peach screen for every mood | Their mood's gradient, its tab, and an opening line in that mood | CR +3–8% |
| 5 | Each pack, said in people | "20 Pulses · 1.25€ / Pulse" | "20 men hear from you first · 1.25€ / Pulse" | CR +3–8% · ARPU +5–10% |

*Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps —
not measured lift for Hush.*

Packs, prices, badges, the 1M+ figure, the moods, the French App Store rating and the
"What do you love most in life?" prompt come from Hush's own in-app screens, website and App Store
listing.

## Run locally

```bash
python3 -m http.server 8000
```
