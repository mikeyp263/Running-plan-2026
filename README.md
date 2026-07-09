# Run Coach Final

A simple offline-capable running plan web app/PWA.

## What is different in this version

- 0 current mileage is allowed.
- Sunday is off by default.
- The app avoids pointless 1-mile filler runs.
- The coach chooses weekly mileage, workout days, long-run day, phases, and paces.
- Old PRs are treated as background only, not current pace targets.
- Workouts do not start early: foundation -> strides/hills -> threshold -> race-specific -> taper.
- Long-run workouts appear only after enough weeks, enough mileage, and the right phase.
- Day-by-day editing is built in.
- Logging adapts the next run and next hard day.

## How to use on phone

Upload this folder to any static host such as Netlify, Vercel, GitHub Pages, or your own web hosting. Open the live URL on your phone.

- iPhone: Safari -> Share -> Add to Home Screen
- Android: Chrome -> menu -> Add to Home screen / Install app

## Notes

This is a coaching logic tool, not medical advice. If pain is sharp, worsening, or changes your stride, stop and get evaluated.
