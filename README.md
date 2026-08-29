# Herbs App - Promotional Landing Page

```
██╗  ██╗███████╗██████╗ ██████╗  ██████╗
██║  ██║██╔════╝██╔══██╗██╔══██╗██╔════╝
███████║█████╗  ██████╔╝██████╔╝███████╗
██║  ██║██╔══╝  ██╔══██╗██╔══██╗╚════██║
██║  ██║███████╗██║  ██║██████╔╝██████╔╝
╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═════╝╚═════╝
```

---

## ◆ PULSE

A great tool with a door nobody can find is a tool nobody uses. This
page is the door: a single, self-contained HTML file that introduces
the [Thai Herbal Formulary App](https://github.com/pharmacist-sabot/herbs-app),
states its benefits, and points new users to the live app - by button
or by QR code. Portable enough to share as one file, styled to match
the app it promotes, built for the moment a pharmacist first hears
the name.

| Single file ▣ | CTA + QR ▣ | Responsive ▣ | Zero deps ▣ |
|---|---|---|---|

*The door - introduce, point, invite - is sealed.*

> Built with one `promotion.html`, one `qr-code.png`, and nothing
> else - the dependency count is the design.
>
> **suradet-ps**, artifact keeper

---

## ◆ IGNITION

One clone, zero build step.

```
⟫ git clone https://github.com/pharmacist-sabot/promote-herbs-app.git
⟫ cd promote-herbs-app
```

Open `promotion.html` in any browser. That is the whole ritual - no
install, no bundler, no server. Deploy the file to any static host:
GitHub Pages, Netlify, or Vercel.

<details>
<summary>Making the QR code live</summary>

1. Generate a QR code pointing at the live app
   (e.g. `https://herbs-app.rxdevman.com/`).
2. Name it `qr-code.png`.
3. Place it in the repo root - the page picks it up.

</details>

---

## ◆ ANATOMY

One page, one message, a single clear direction.

- **Introduces** - the page outlines the formulary app's key benefits
  and features - what the tool does, in the words of its users.
- **Directs** - a prominent call-to-action button and a QR section
  carry visitors to the live application - one glance, one tap.
- **Matches** - the styling borrows the main app's theme, so the
  landing page and the tool feel like one product, not two.
- **Fits** - the layout is fully responsive - the same door opens on
  the ward desktop and the phone in the pocket.
- **Travels** - one file, zero dependencies: the page can be shared
  as an attachment, served as a static file, or hosted anywhere.

---

## ◆ RITUALS

**The core ceremony** - the introduction:

1. Open the page - on the projector in the meeting, or on the phone
   beside the pharmacist.
2. Read the benefits; see the app's face.
3. Tap the button or scan the QR - the formulary opens on the
   visitor's own device.
4. Done. The door did its job and stepped aside.

**The ceremony of the single file** - the page survives email, USB,
and the hospital's policy-restricted wifi: one HTML file, nothing to
install, nothing to break.

**The ceremony of the QR** - the code on the poster and the button on
the screen point at the same promise: the app is one scan away.

---

## ◆ ECHOES

**Where this artifact is heading**

```
introduce ▸ benefits and features overview ─────────────────────────── ▸ sealed
direct    ▸ CTA button + QR code ───────────────────────────────────── ▸ sealed
match     ▸ themed after the main app ──────────────────────────────── ▸ sealed
travel    ▸ single-file, zero-dependency portability ───────────────── ▸ sealed
```

**Raising the artifact** - the whole page lives in `promotion.html`;
the QR in `qr-code.png`. Open an issue first to discuss a change.

**Status** - the page is static by design; any static host serves it.

---

```
  ─────────────────────────────────────────
   The best landing page is the one
   that gets out of the way.
  ─────────────────────────────────────────
```

Open source.