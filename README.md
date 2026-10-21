# Syrian Slots Game

Android APK project for a six-slot Syrian-currency-themed slots game.

## Build
The included GitHub Actions workflow builds a debug APK when pushed to the `main` branch or run manually from Actions. The artifact is named `Syrian-Slots-APK`.

## Game rules implemented
- Six slots and seven symbols: 10, 25, 50, 100, 200, 500 Syrian-lira-style symbols, plus a coin symbol valued at 20 points.
- A spin costs 10 points.
- 2–3 matching symbols pay one quarter of that symbol's value.
- 4–5 matching symbols pay half of that symbol's value.
- 6 matching symbols pay the full value.
- This is a points-only demo; it does not process real money or withdrawals.
