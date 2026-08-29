# JC Lighting Collection

Open-source reinterpretations of every collection in **Peter Bristol's Visual Comfort lineup** — rebuilt with better specs, better materials, and honest small-batch pricing. Smart by default.

**Site:** https://jerbotclaw-max.github.io/jc-lighting/

## The lineup (12 collections)

| Their collection | Their retail* | JC edition | Est. DIY BOM | Est. kit |
|---|---|---|---|---|
| Bend (Signature) | $499–$899 | JC Bend | $50–$100 | $125–$249 |
| Dot (Signature) | $869–$2,069 | JC Dot | $61–$104 | $159–$259 |
| Overture (Signature) | $749–$5,299 | JC Overture | $84–$236 | $199–$569 |
| Quarter Sphere (Signature) | $999 | JC Quarter Sphere | $56 | $135 |
| Racetrack (Signature) | $2,199–$3,399 | JC Racetrack | $104–$188 | $249–$459 |
| Helium (Modern) | $479–$6,759 | JC Helium | $59–$250 | $149–$619 |
| Cymbal (Modern) | $1,579–$2,259 | JC Cymbal | $79 | $189 |
| Interlace (Signature) | $1,419 | JC Interlace | $69 | $169 |
| 60-40 (Signature) | $2,199 | JC Sixty-Forty | $99 | $239 |
| Stance (Signature) | $619–$1,199 | JC Stance | $59 | $149 |
| Trace (Signature) | ≈$2,500–$3,500 est. | JC Trace | $152 | $369 |
| Shielded (Signature) | ≈$399 est. | JC Shielded | $34 | $95 |

\* Dealer listings (Capitol Lighting, Lumens, Foundry Lighting, Lighting New York), Aug 2026. All JC numbers are estimates, not quotes.

## Shared platform contract

- GetBrighter-class emitters integrated: CRI ≥ 97, R9 > 90, TM-30 RF ≥ 90 (Seoul SunLike / Bridgelux Thrive / Cree tier); tunable white 2700–6500 K; RGBW option on scene fixtures (mixes to ~CRI 92 — high-CRI tunable-white variant standard)
- 100–240 V drivers, >25 kHz PWM, <1% flicker at all levels, 0–100% dimming, PF > 0.9
- 50,000 h LED life with thermal derating; UGR < 19 diffusers
- ESP32-C3 (single-body mains fixtures, Matter-over-WiFi) or nRF52840 (multi-body bus fixtures — Helium, Trace; BLE-first, Matter-over-Thread option)
- BLE provisioning, Matter, Home Assistant, local REST/mDNS API
- USB-C service port on every unit; replaceable LED boards throughout
- JC Boost: firmware-gated multi-emitter overdrive — 20,000+ lm on multi-emitter editions (Racetrack 48" Boost 20,600 lm, Trace dual-rail 20,400 lm, Helium Gallery 20,800 lm); honest per-form-factor max + a bigger-edition wink everywhere else
- Solid brass / machined & extruded aluminum / cast stone + real glass vs original plated steel

## JC Light OS

One Apache-2.0 firmware for the whole collection; per-fixture profiles are device-tree + calibration blobs. See `lightos.html` on the site.

## Licensing

- Firmware: Apache-2.0
- Hardware (KiCad, STL/STEP, when released): CERN-OHL-H
- Documentation/site: CC-BY-SA-4.0

## Disclaimer

Fan-made open reinterpretations of publicly retailed designs. **Not affiliated with, endorsed by, or licensed by Visual Comfort & Co. or Peter Bristol.** No proprietary CAD, drawings, renderings, or photography used — all descriptions, specifications, estimates, and artwork are original. Prices/specs are estimates; verify before you build.
