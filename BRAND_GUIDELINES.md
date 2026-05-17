# Madame Anaconda — Brand Guidelines
*Version 1.0 · May 2026*

---

## 01 · Brand Essence

Madame Anaconda is a drag performer, activist, and icon. The brand exists at the intersection of high glamour and radical self-expression — dark luxury with a pulse. Everything produced under this name should feel like it could live in a velvet-draped theater one moment and on the front line of a pride march the next.

**Three words that define the brand:**
- **Venomous** — sharp, bold, not here to be ignored
- **Luminous** — glamorous, theatrical, visually arresting
- **Unapologetic** — confident, political, joyfully defiant

**Brand tagline:**
> *She slithers. She shimmers. She slays.*

**Brand statement:**
> *Drag is not a crime. It is an art form, a revolution, and a love letter to freedom.*

---

## 02 · Color Palette

The palette is dark luxury — obsidian foundations with jewel-toned accents. Colors are never flat; they live in gradients and glows.

### Primary Colors

| Name       | Hex       | Use |
|------------|-----------|-----|
| Obsidian   | `#07070f` | Primary background — the foundation of everything |
| Midnight   | `#0f0f1c` | Secondary background, section layering |
| Slate      | `#181828` | Cards, panels, elevated surfaces |

### Accent Colors

| Name  | Hex       | Use |
|-------|-----------|-----|
| Gold  | `#c9a84c` | Primary accent — headlines, borders, CTA highlights, links |
| Rose  | `#c8415a` | Energy, activism, urgency — used in gradients and highlights |
| Plum  | `#7c3aed` | Depth and drama — always paired with rose or gold, never alone |
| Sage  | `#4a9d7a` | Balance and life — used sparingly for contrast against the dark palette |

### Text Colors

| Name  | Hex                        | Use |
|-------|----------------------------|-----|
| Cream | `#f5ede3`                  | Primary body text |
| Muted | `rgba(245,237,227,0.55)`   | Secondary text, captions |
| Ghost | `rgba(245,237,227,0.28)`   | Fine print, metadata |

### Signature Gradient
The brand gradient runs gold → rose → plum and is used on the primary wordmark and hero headlines only.

```
linear-gradient(135deg, #c9a84c 0%, #c8415a 45%, #7c3aed 80%, #c9a84c 100%)
```

### Usage Rules
- **Never** place accent colors on white or light backgrounds
- **Always** apply the noise/grain texture over backgrounds for depth
- Glow effects (radial gradients in plum and rose) should be subtle — opacity 0.06–0.18 maximum
- Gold is the trust color — use it for anything the audience needs to act on

---

## 03 · Typography

Typography is theatrical and authoritative. There are three typefaces in the system — each has a defined role and they should not be swapped.

### Display — Cinzel Decorative
**Use for:** Name wordmark, section titles, navigation, buttons, all-caps labels

Cinzel Decorative carries the crown. It is Roman-inspired, commanding, and impossible to ignore. It should always feel like it's being announced.

- Weight: 700 or 900 only
- Tracking: 0.04em–0.22em depending on size
- Never set in lowercase
- Never italic

```
font-family: 'Cinzel Decorative', cursive;
font-weight: 900;
letter-spacing: 0.04em;
```

### Editorial — Playfair Display
**Use for:** Pull quotes, prices, statistics, short callout text

Playfair Display bridges glamour and readability. Use it when Cinzel Decorative would be too heavy and Cormorant Garamond too delicate.

- Weight: 400 or 700
- Italic allowed and encouraged for quotes
- Never all-caps

```
font-family: 'Playfair Display', serif;
font-style: italic;
```

### Body — Cormorant Garamond
**Use for:** Body copy, descriptions, email, long-form text, eyebrow labels

Cormorant Garamond is the voice between the performances. Elegant, readable, and always slightly italic for character.

- Weight: 300 or 600
- Italic is the default personality; upright for structured content
- Tracking on uppercase labels: 0.3em–0.5em

```
font-family: 'Cormorant Garamond', Georgia, serif;
font-style: italic;
font-size: clamp(1rem, 1.8vw, 1.28rem);
line-height: 1.95;
```

### Type Scale (web)

| Role           | Size                        | Font               |
|----------------|-----------------------------|--------------------|
| Hero title     | clamp(3.5rem, 11vw, 10rem)  | Cinzel Decorative  |
| Section title  | clamp(2.4rem, 7vw, 6rem)    | Cinzel Decorative  |
| Pull quote     | clamp(1.25rem, 2.3vw, 1.9rem)| Playfair Display  |
| Body           | clamp(1.05rem, 1.8vw, 1.28rem)| Cormorant Garamond|
| Label/eyebrow  | 0.75rem–0.95rem             | Cormorant Garamond |
| Button         | 0.52rem–0.6rem              | Cinzel Decorative  |

---

## 04 · Logo & Name

### Wordmark
The primary wordmark is **MADAME ANACONDA** set in Cinzel Decorative 900 weight, with the signature gold→rose→plum gradient applied.

The secondary treatment is the outlined version — transparent fill with a 1px cream stroke at 35–45% opacity. This is used as a counterpoint to the gradient wordmark and should always appear beneath or alongside it.

### Name Usage Rules
- Full name: **Madame Anaconda** — preferred in all contexts
- Short form: **Madame** — acceptable in secondary references within the same piece
- Never: "MA," "M.A.," or any other abbreviation
- The word "Madame" is always spelled with the final **e** — not "Madam"
- In running text: *Madame Anaconda* (Title Case)
- As a wordmark/display: **MADAME ANACONDA** (Cinzel Decorative, all-caps rendering)

### Crown Symbol 👑
The crown emoji is the brand's informal icon. Use it:
- In digital/social contexts as a standalone identifier
- Before or after the name for warmth
- Filtered with a gold glow: `filter: drop-shadow(0 0 20px rgba(201,168,76,0.8))`

Never replace the crown with a different emoji or symbol.

### Clear Space
Always maintain a minimum clear space around the wordmark equal to the cap height of the "M" in the current size.

---

## 05 · Voice & Tone

Madame Anaconda speaks in first person. The brand is the performer — never corporate, never distanced.

### Core Voice Traits

**Theatrical** — Everything is a performance. Even a simple announcement should have presence.
> ✗ "New merch available now"
> ✓ "The wardrobe just got more dangerous. New pieces are here."

**Sharp** — Wit is a weapon. Sentences land. No filler, no hedging.
> ✗ "We hope you'll consider coming to our upcoming show"
> ✓ "Be there. Or don't — but you'll regret it."

**Warm underneath** — The fierceness is a cape, not a wall. There's genuine love for the community beneath every barb.
> ✗ "Thank you for your purchase"
> ✓ "You just became part of something. Welcome to the revolution."

**Political without being preachy** — The activism is woven in, not bolted on. State truths, don't lecture.
> ✗ "We believe drag should be accepted everywhere"
> ✓ "Drag is not a crime. It never was."

### Tone by Context

| Context         | Tone                                      |
|-----------------|-------------------------------------------|
| Social media    | Fierce, playful, reactive, first-person   |
| Email           | Intimate, conspiratorial, like a letter   |
| Website         | Theatrical, declarative, present tense    |
| Press/bios      | Third person, authoritative, mythic       |
| Merchandise     | Punchy slogans, short, bold statements    |
| Activism content| Direct, clear, passionate — never preachy |

### Words We Use
venomous · luminous · unapologetic · revolution · freedom · darling · icon · queen · slither · shimmer · slay · fierce · defiant · art form · love letter

### Words We Avoid
amazing · awesome · super · excited to announce · we're thrilled · synergy · content · collab (preferred: *collaboration*) · haters

---

## 06 · Imagery & Visual Style

### Photography Direction
- **Lighting:** Dramatic, high-contrast — deep shadows, single strong light source or practical glow
- **Color grade:** Desaturated backgrounds with the subject popping; warm gold/rose tones on skin
- **Mood:** Theatrical stillness OR caught mid-performance — nothing in between
- **Framing:** Confident. The subject owns the frame. Never apologetic cropping.
- **Background:** Dark, abstract, or architectural. Never generic stock backgrounds.

### Graphic Design Principles
- **Dark first** — compositions start from black and add light, never the reverse
- **Texture always** — film grain or noise overlay at 30–40% opacity on every surface
- **Borders and frames** — thin gold lines (1px, rgba(201,168,76,0.15–0.55)) create architectural containment
- **Corner marks** — small L-shaped corner accents in gold signal craft and intentionality
- **Glow, not neon** — light effects are warm and diffused, never harsh neon

### What to Avoid
- Bright white backgrounds
- Flat color fills without texture
- Clip art, generic icons, or stock illustrations
- Rounded rectangles (use sharp corners — 0px border-radius)
- Anything that reads as "corporate Pride month"
- Comic Sans, Impact, or decorative fonts other than the brand system

---

## 07 · Social Media

### Platform Presence
- **TikTok** — Primary platform. Raw, performance-forward, reactive to trends. First-person voice.
- **Instagram** — Visual archive of looks, show moments, and quotes. More curated than TikTok.

### Content Pillars
1. **Performance** — Show clips, behind-the-scenes, rehearsal footage
2. **The Look** — Drag transformation, costume details, makeup process
3. **The Message** — Activism, commentary, community moments
4. **Merch & Commerce** — Product launches, styling content, purchase prompts
5. **Personality** — Humor, reactions, daily life through the Madame lens

### Caption Style
- Short is strong. One punchy line beats three mediocre ones.
- End with a question or statement, not a hashtag dump
- Hashtags (if used): 3–5 targeted, always last, never in the body copy
- Emojis: 👑 🐍 🌈 — used sparingly and with purpose

---

## 08 · Merchandise Guidelines

### Brand Statement Merchandise
The anchor phrase **"Drag Is Not A Crime"** is the flagship statement. It should always appear:
- In a legible, high-contrast treatment
- With Madame Anaconda credited (on tag or print)
- Never in a font that conflicts with the brand system

### Collaboration Protocol
Official merchandise is produced through **Badditude Apparel**. Any third-party collaboration must be approved and should:
- Use the brand color palette or direct photo of the performer
- Credit: *Madame Anaconda × [Partner]*
- Maintain quality standards — no thin fabric, no cheap finishes

---

## 09 · Brand Don'ts

| Don't | Why |
|-------|-----|
| Use the brand to "both sides" drag activism | The brand has a clear position — drag is art and drag is valid |
| Pair the wordmark with generic stock photos | It undermines the theatrical identity |
| Use the gradient on body text | Reserve it for display use only — it's too decorative to read |
| Post in a voice that's uncertain or apologetic | Madame Anaconda is never unsure of herself |
| Use bright/saturated colors without dark grounding | The palette only works on dark foundations |
| Abbreviate, rename, or rebrand without authorization | The name and identity are the performer's — protect them |

---

## 10 · Quick Reference Card

```
COLORS          Gold #c9a84c  ·  Rose #c8415a  ·  Plum #7c3aed
                Sage #4a9d7a  ·  Obsidian #07070f  ·  Cream #f5ede3

FONTS           Display    → Cinzel Decorative 900
                Editorial  → Playfair Display 400/700 italic
                Body       → Cormorant Garamond 300/600 italic

TAGLINE         She slithers. She shimmers. She slays.
STATEMENT       Drag is not a crime. It is an art form,
                a revolution, and a love letter to freedom.

WEBSITE         madameanaconda.com
TIKTOK          @madameanaconde

CONTACT         booking@madameanaconda.com
WEB BY          Softseas Digital · softseasdigital.com
```

---

*These guidelines exist to protect and amplify the Madame Anaconda brand. When in doubt, ask: does this feel like the Queen would approve? If yes — proceed. If not — start over.*
