<div align="center">

<img src="https://raw.githubusercontent.com/projectviridis/web/main/WEB/brand/org/banner.svg" alt="Project Viridis — open-source submarine" width="100%"/>

<br/>

**An open-source submarine you can 3D-print, wire up and dive in your own pool.**
Water pumps instead of propellers · a ballast tank built into the hull · live camera on a bench-friendly budget.

<br/>

[![Website](https://img.shields.io/badge/WEBSITE-projectviridis.dev-4BFF9A?style=for-the-badge&labelColor=04101C)](https://www.projectviridis.dev)
[![Docs](https://img.shields.io/badge/BUILD_GUIDE-documentation-2C74B3?style=for-the-badge&labelColor=04101C)](https://www.projectviridis.dev/dokumentace)
[![Depth](https://img.shields.io/badge/RATED_DEPTH-20_m-0E5A63?style=for-the-badge&labelColor=04101C)](https://www.projectviridis.dev)

</div>

---

## `> sounding`

```text
 surface ─────────────────────────────────────────  0 m
    │   print      PETG · 40 % gyroid infill
    │   wire       Arduino Nano · TB6612FNG · IMU & depth sensors
    ▼   seal       IP68 switch · SP13 connector · O-rings
 ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─  5 m   first test, in the pool
    │   ballast    peristaltic pump ⇄ space between two ribbed hull walls
    │   steer      4 or 6 water-jet pumps, nothing spinning outside
    ▼   see        analog FPV camera behind a clear window
 ═════════════════════════════════════════════════ 20 m  rated depth
```

## `> what makes it different`

| | |
|---|---|
| 💧 **Water, not blades** | Internal pumps and jets push the hull around. No exposed propeller to snag weeds, fingers or fishing line. |
| 🫧 **A ballast tank that *is* the hull** | No bag, no bladder: the ballast fills the cavity between the two ribbed walls of the body. A peristaltic pump floods it to sink and empties it to rise. |
| 🖨️ **Printable by anyone** | Hull and cover in PETG, 40 % gyroid infill on both variants. STL and STEP models are free. |
| 🔧 **Two variants, one body** | Same hull, cover, camera, battery and ballast. They differ in propulsion (4 or 6 pumps), sensors and electronics. |
| 📖 **Documented like a product** | Seven build steps, a full bill of materials, wiring and a price per variant — in Czech, English and French. |

## `> repositories`

| Repo | What lives there |
|---|---|
| [**web**](https://github.com/projectviridis/web) | The website, documentation engine and interactive 3D model of the submarine you see at [projectviridis.dev](https://www.projectviridis.dev). |
| *more soon* | Firmware, CAD (STL / STEP) and the control station will land here as they get cleaned up for release. |

## `> build it`

```text
01  print the hull and cover      PETG · 40 % gyroid
02  fit the electronics           Nano · TB6612FNG · sensors
03  battery & ballast             12 V lead-acid · peristaltic pump
04  camera & window               analog FPV behind clear glazing
05  close the cover
06  mount the jets                four or six, per variant
07  seal & test                   pool first, open water later
```

➡️ Full guide with pictures: **[projectviridis.dev/dokumentace](https://www.projectviridis.dev/dokumentace)**

## `> who`

Built by students and mentors at [VOŠ a SPŠE Plzeň](https://www.spseplzen.cz). Questions, ideas or want to build one yourself? Open an issue or say hi through the [contact form](https://www.projectviridis.dev/kontakt).

<div align="center">

<sub>`depth 0.0 m` · all systems nominal · <a href="https://www.projectviridis.dev">dive in →</a></sub>

</div>
