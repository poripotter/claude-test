---
message: "CoUp is the AI coach that builds your workout plan, runs your sessions, and shows you getting stronger."
audience: Persian-speaking gym-goers and online fitness coaches
mode: autonomous
canvas: 1080x1080 @ 30fps
duration: 32.2s
language: fa (RTL)
---

# CoUp — Product Demo Breakdown (Persian)

Persistent frame (index.html): brand «کوآپ» + Persian timecode top-right, «دموی محصول / کالبدشکافی»
top-left, 16:9 preview card, ruler + playhead travelling right→left, section tabs
هوک · معرفی · دمو · رشد · اقدام (widths proportional to section length), «سناریو» label.
Motion language copied from the Skedul.AI reference: blur-wipe type, 3D-tilted UI, cursor clicks,
camera push-ins, blue panel grow, voice orb, navy "growth" stage, CTA click, end dim.

## Frame 1
- status: built
- src: compositions/hook.html
- window: 0.0–7.6s (section هوک 0–7.2)
- rules: depth-of-field-blur, cursor-click-ripple, coordinate-target-zoom, 3d-page-scroll (tilt)
- beat: «بدون برنامه؟» ("No plan?") wipes in right→left from blur. A day calendar
  (چهارشنبه، ۱ مهر ۱۴۰۵) swings in on a 3D tilt; cursor clicks «امروز»; the Mehr 1405 month
  popover springs open; camera pushes in while the day hops ۱→۲→۳ and the day's session chips
  swap (روز سینه → روز پا → استراحت فعال). Everything melts into a blue blur.

## Frame 2
- status: built
- src: compositions/reveal.html
- window: 7.2–13.3s (section معرفی 7.2–13.0)
- rules: card-morph-anchor, gsap-effects (typewriter)
- beat: wordmark «کوآپ» blurs in inside dashed guide lines; lines collapse to a seed that grows
  into a full blue panel; typewriter tagline «مربی هوشمند تو، همیشه همراهت»; panel pinches down
  toward the voice orb.

## Frame 3
- status: built
- src: compositions/demo.html
- window: 12.9–23.0s (section دمو 13.0–22.8)
- rules: sine-wave-loop (waveform), 3d-camera-flight, control-target-sync
- beat: AI voice orb with live waveform; prompt «یه برنامه ۴ روزه بساز که قوی‌تر بشم».
  Generated plan items fly in close to camera (گرم کردن، پرس سینه ۴×۸ ۶۰ کیلو، اسکوات ۵×۵،
  سوپرست، سرد کردن) and pull back into the «برنامه امروزت» card. Day schedule rises in;
  a purple block sweeps onto bench press → ۶۲٫۵ کیلو with badge «افزایش تدریجی بار · +۲٫۵ کیلو».

## Frame 4
- status: built
- src: compositions/growth.html
- window: 22.6–28.4s (section رشد 22.8–28.0)
- rules: stat-bars-and-fills, counting-dynamic-scale, svg-path-draw, ambient-glow-bloom
- beat: navy stage; «جلسه امروز» session tracker (sets marked «انجام شد ✓», rest timer counting
  down) tilts in 3D under a light band; loading bar hands off to «گزارش پیشرفت تو»:
  strength score count-up ۴٫۷/۵ + weekly bars, ۲۱-day streak, time-split donut, new records.

## Frame 5
- status: built
- src: compositions/cta.html
- window: 28.0–32.2s (section اقدام 28.0–32.2)
- rules: cta-morph-press / physics-press-reaction, cursor-click-ripple
- beat: «کوآپ.» wordmark wipes in, «مربی هوشمند بدنسازی، توی جیبت», button
  «همین حالا رایگان شروع کن» pressed by the cursor, coachupgrade.ir; whole frame dims at the end.
