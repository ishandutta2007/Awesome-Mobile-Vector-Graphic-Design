# Awesome-Mobile-Vector-Graphic-Design

# Top Mobile Vector Graphic Design Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Touch-Optimized SVG Editing, iPad Illustration Apps & Android Vector Tools*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Mobile Vector Graphic Design**. These tools bring vector illustration to tablets and phones — paths, bezier curves, layers, and SVG export — with a spectrum running from polished commercial iPad apps to open-source Android editors that run entirely offline.

**Examples** include Inkpad Libre, FreePaint, Butterfly, VectorTouch, and Inky (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, touch-optimized SVG editing, and offline mobile design — especially relevant as **Inkpad Libre revives the classic open-source iPad vector app** under the MPL 2.0 license , and **FreePaint** offers native SVG editing on Android via F-Droid .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **Adobe Illustrator on iPad** — **The reference professional vector tool for tablets.** Full Illustrator toolset reimagined for touch and Apple Pencil, with Creative Cloud sync and .ai file compatibility. **Subscription required** (Creative Cloud plan). **Best for professional designers** already in Adobe's ecosystem who need desktop-class vector power on an iPad.

- **Affinity Designer for iPad** — **The one-time-purchase professional alternative.** Full vector and raster workspace with native CMYK, Pantone libraries, and PSD/AI import/export. **One-time purchase** (~$18.49). **Best for designers** wanting professional-grade iPad illustration without subscriptions.

- **Vectornator (Linearity Curve)** — **The free Apple-ecosystem vector design tool.** Free plan with paid Pro tiers, Apple Pencil support, auto-trace, and Boolean operations. **Trade-offs**: Apple-only, no Android or Windows version. **Best for iPad users** wanting a polished free vector app with Apple Pencil integration.

- **Concepts** — **The infinite-canvas sketching app.** Vector-based drawing on an infinite canvas with adjustable precision, ideal for ideation and wireframing. **Free tier with paid Pro**. **Best for designers** wanting a flexible ideation space rather than precise illustration.

## Open-Source GitHub Projects

- **Inkpad Libre** — **The open-source iPad vector illustration app, revived.** **Mozilla Public License 2.0**, free on the App Store with the source available on GitHub . **A revival of Steven Sprang's original Inkpad**, updated for modern iPadOS versions . **Full vector toolset**: pen tool for bezier paths, compound paths, masks, groups, text objects with custom font import, gradient fills, arbitrary stroke dash patterns, Boolean operators (Unite, Intersect, Exclude, Subtract Front), and unlimited layers with rename/rearrange/hide/lock . **Designed for performance** — handles hundreds to thousands of shapes without lag . **Export to SVG, PDF, PNG, and JPEG**, with direct Dropbox and Files app integration . **The honest caveat**: **iPad-only** and the last update was in 2020 — it works on modern iPadOS but is not actively developed . **Best for iPad users** wanting a free, open-source vector illustration app with a proven feature set, accepting that it is a stable but dormant project .

- **FreePaint** — **The native Android vector drawing app.** **Open-source, available on F-Droid**, with **Material Design 3** and dynamic colors . **Draw open or closed paths** with customizable fill/stroke colors and stroke sizes, **erase shapes from closed paths or points from open paths**, and **save/load SVG files** . **Selection tool** for marquee-selecting and moving paths . **Pan and pinch-to-zoom** . **Requires Android 7.0+** . **The honest caveat**: **basic feature set** — no layers, no Boolean operations, no text tools, and no gradient fills . **Best for Android users** wanting a simple, offline SVG drawing app without ads or subscriptions .

- **Butterfly (Linwood Butterfly)** — **The infinite-canvas note-taking and drawing app.** **AGPL-3.0 licensed**, available on **Android, desktop, and web** . **Endless workspace** for placing notes, sketches, diagrams, images, and documents wherever they make sense . **Stylus, touch, or mouse input**, with **text and Markdown typing**, shapes, images, and **PDF/SVG import** . **Export to PDF, SVG, images, or portable Butterfly files** . **Layers, pages, page folders, areas, waypoints, reusable packs, palettes, and text styles** — almost everything remains editable . **Privacy-first**: works offline, files stored on your device, optional WebDAV/Nextcloud sync, **no required account or subscription** . **Best for Android tablet users** wanting an infinite-canvas vector app that doubles as a note-taking and diagramming tool .

- **VectorTouch** — **The touch-optimized SVG editor for Android.** **MIT licensed**, bringing the **GodSVG** editing experience to mobile with a touch-friendly interface . **Direct SVG file editing** on Android devices . **Available on Google Play Store**, with direct APK downloads (arm32, arm64, x86_64) from GitHub releases . **The honest caveat**: **still in development** — may have bugs, and the feature set is narrower than desktop editors . **Best for Android users** wanting direct SVG markup editing with a mobile-optimized interface .

- **Inky (Inkscape for Android)** — **The unofficial Inkscape adaptation for Android.** **GPLv3 licensed**, a paid app (~R$ 9,99) that runs **the full Linux Inkscape desktop version** on Android via a compatibility layer . **Full Inkscape feature set**: vector shapes, text, gradients, bitmap tracing, and SVG import/export . **Touch controls**: tap to left-click, slide to move mouse, pinch to zoom, two-finger tap for right-click, and on-screen keyboard access . **The honest caveat**: **it is a desktop app running on a phone** — the interface is not touch-native, and using it without a stylus and tablet is cumbersome . **Best for Android power users** who specifically need Inkscape's full feature set on the go, accepting the awkward touch experience .

### Additional Strong Open-Source Options

- **GodSVG** — **The structured SVG editor with low abstraction.** Free, open-source, available on **Android** alongside desktop platforms . **Modify individual SVG elements** via a user-friendly interface while generating **clean, optimized, human-readable code in real time** . **Best for developers and designers** wanting precise SVG markup control on mobile .
- **Dodeclusters** — **The circle-based vector editor for mobile and desktop.** **Beta-stage**, built with Compose Multiplatform, supporting **Android 7.0+**, desktop, and web . **Infinite canvas and zoom**, circle geometry instrumentation, dynamic expression-dependency tree, undo/redo, and **safe SVG export** . **Best for experimental designers** wanting a mathematically-driven vector tool on Android, accepting beta-stage stability .
- **Fossify Paint** — **The privacy-focused Android drawing app.** **Open-source, available on F-Droid**, with brush size/color customization, canvas background options, and **PNG, JPG, and SVG export** . **Works completely offline** with no intrusive permissions . **The honest caveat**: **raster-first** — SVG export is supported but the drawing model is pixel-based, not true vector path editing . **Best for simple doodling and sketching** on Android with privacy in mind .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Mobile vector design tools differ significantly in platform support, touch optimization, and feature depth. **Inkpad Libre is the most complete open-source iPad vector app** with a full illustration toolset and SVG/PDF export, but **it is iPad-only and has not been updated since 2020** . **FreePaint is the simplest Android SVG editor** — it saves real SVG files but lacks layers, text, and Boolean operations . **Butterfly is an infinite-canvas tool**, not a traditional vector illustrator — it excels at notes and diagrams but is not designed for precise bezier illustration . **VectorTouch is still in development** and may have bugs . **Inky runs full desktop Inkscape on Android**, but the experience is not touch-native — a stylus and tablet are strongly recommended . **The choice often comes down to platform**: iPad users have Inkpad Libre, Android users have FreePaint or Butterfly, and power users who need Inkscape's full toolset can accept Inky's compromises.
- Self-hosted open-source solutions require proper app installation from F-Droid or GitHub releases (not always the Play Store), and awareness that mobile vector editors are limited by available screen size and touch precision compared to desktop tools.

---

**Made for mobile designers, illustrators, and developers choosing vector design tools that match their tablet platform and touch workflow.**
Let's make mobile vector graphic design more open, touch-optimized, and offline-capable.
