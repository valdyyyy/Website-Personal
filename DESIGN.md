---
name: Premium Birthday Aesthetic
colors:
  surface: '#fef8f8'
  surface-dim: '#ded9d9'
  surface-bright: '#fef8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f2f2'
  surface-container: '#f3ecec'
  surface-container-high: '#ede7e7'
  surface-container-highest: '#e7e1e1'
  on-surface: '#1d1b1b'
  on-surface-variant: '#4d4447'
  inverse-surface: '#323030'
  inverse-on-surface: '#f5efef'
  outline: '#7f7478'
  outline-variant: '#d0c3c7'
  surface-tint: '#6b5a60'
  primary: '#6b5a60'
  on-primary: '#ffffff'
  primary-container: '#fce4ec'
  on-primary-container: '#76646b'
  inverse-primary: '#d7c1c8'
  secondary: '#715478'
  on-secondary: '#ffffff'
  secondary-container: '#f8d4fe'
  on-secondary-container: '#75597c'
  tertiary: '#7b5549'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffe5dd'
  on-tertiary-container: '#876053'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f4dce4'
  primary-fixed-dim: '#d7c1c8'
  on-primary-fixed: '#25181e'
  on-primary-fixed-variant: '#524249'
  secondary-fixed: '#fad7ff'
  secondary-fixed-dim: '#debbe4'
  on-secondary-fixed: '#291231'
  on-secondary-fixed-variant: '#583d5f'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#edbbac'
  on-tertiary-fixed: '#2f140b'
  on-tertiary-fixed-variant: '#613e33'
  background: '#fef8f8'
  on-background: '#1d1b1b'
  surface-variant: '#e7e1e1'
typography:
  display-romantic:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  letter-cursive:
    fontFamily: Epilogue
    fontSize: 20px
    fontWeight: '300'
    lineHeight: '1.8'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  xs: 0.25rem
  sm: 0.5rem
  md: 1rem
  lg: 2rem
  xl: 4rem
  gutter: 1.5rem
  margin: 2rem
---

## Brand & Style

This design system is built to evoke the feeling of receiving a high-end, physical luxury gift box in a digital space. The brand personality is deeply romantic, intimate, and curated, drawing heavy inspiration from the "Soft Girl" and "Old Money" aesthetics found on Pinterest and TikTok. 

The visual language centers on **Glassmorphism**, using translucent layers and high-quality backdrop blurs to create a sense of depth and weightlessness. It avoids harsh lines, opting instead for glowing edges and ethereal transitions. The target audience values personalization and "aesthetic" presentation, expecting an experience that feels less like a utility and more like a keepsake. Key emotional drivers are warmth, surprise, and a premium sense of exclusivity.

## Colors

The palette is a curated selection of soft pastels that mimic the hues of a sunset or a bouquet of fresh peonies. 

- **Soft Pink (#FCE4EC):** The primary brand color, used for major surfaces and soft highlights.
- **Cream (#FFF9E1):** The base background color, providing a warmer, more "paper-like" feel than pure white.
- **Lavender (#E1BEE7) & Peach (#FFCCBC):** Used for secondary accents, gradients, and decorative heart elements to add depth to the glass layers.
- **Elegant Gold (#D4AF37):** Used sparingly for "Glowing Accents," such as button borders, iconography details, and decorative "sparkles."
- **White (#FFFFFF):** Utilized primarily for high-transparency glass overlays and pure highlights.

## Typography

Typography is used to create a clear hierarchy between "System UI" and "Emotional Content."

- **Headings (Playfair Display):** Should be set with tight letter-spacing. Use for names, birthday wishes, and section titles.
- **Body (Inter):** Used for functional text, instructions, and small labels to maintain modern legibility.
- **Love Letters (Epilogue):** While a geometric sans, when used in thin weights with increased line height and italicized, it serves as the modern "Aesthetic Handwriting" for personal notes, mimicking clean digital journaling.
- **Editorial Flourish:** Large display quotes should always be in Playfair Display to emphasize the premium nature of the gift.

## Layout & Spacing

The layout philosophy follows a **Fluid Grid** with generous white space to allow the "Glass" elements room to breathe. 

- **Safe Margins:** A minimum of 32px (2rem) margin is required on mobile to ensure the UI feels expansive and luxurious rather than cramped.
- **Vertical Rhythm:** Use large 64px (4rem) spacers between major content sections (e.g., between the "Hero Greeting" and the "Photo Gallery") to create a sense of discovery while scrolling.
- **Alignment:** Center-alignment is preferred for hero sections to emphasize the "gift" presentation, while body content should follow a standard left-aligned grid for readability.

## Elevation & Depth

Depth is not created through traditional dark shadows, but through **Tonal Stacking** and **Backdrop Filters**.

- **The Base:** The Cream (#FFF9E1) background serves as the canvas.
- **The Glass Layer:** Elevated cards use `backdrop-filter: blur(20px)` and a white border with 20% opacity. 
- **The Glow:** Instead of a black shadow, use a "Bloom" effect: a soft, wide-spread outer glow using the Primary Pink or Gold color at 10-15% opacity.
- **Interactivity:** When an element is touched or hovered, the blur intensity should increase, and the gold border should "brighten" to simulate a light source moving behind the glass.

## Shapes

The shape language is organic and soft.

- **Primary Radius:** All standard cards and buttons use a 1rem (rounded-lg) radius to maintain a soft, friendly appearance.
- **Heart-Shaped UI:** Distinctive "Action" elements (like the 'Open Gift' button or profile frames) should utilize a soft heart silhouette or a "squircle" that approximates a heart shape.
- **Glass Containers:** Use thin, 1px borders in a lighter shade than the surface itself to define edges without adding visual weight.

## Components

- **The Birthday Button:** A large, pill-shaped button with a gold-to-peach gradient and a persistent soft pulse animation.
- **Memory Cards:** Glassmorphic cards used to display photos. They feature a slight 2-degree tilt to mimic physical polaroids dropped on a table.
- **Love Letter Inputs:** Text fields should have no background, only a bottom border in Gold, mimicking ruled stationary.
- **Sparkle Chips:** Small, non-interactive tags used for "Vibe Labels" (e.g., "Sweet," "Magical," "Forever"). These should have a subtle shimmer animation.
- **Confetti Overlay:** A custom component that triggers a slow-motion fall of heart-shaped particles and gold dust when the gift is "unwrapped."
- **Floating Hearts:** Use soft-focus, blurred heart shapes in the background that move slightly based on device orientation (parallax).