# Celestial Luxury Narrative

## Brand & Style

This design system embodies the intersection of high-precision aerospace engineering and the raw, visceral beauty of the natural horizon. It is designed for an ultra-premium rooftop environment where the "Golden Hour" is an eternal state. The aesthetic is **Cinematic Glassmorphism**—a blend of technical minimalism and warm, atmospheric luxury.

The target audience is the global elite who value exclusivity, precision, and sensory experiences. The UI must evoke a sense of "awe-inspired calm," utilizing vast negative space, high-contrast editorial typography, and translucent materials that feel as light as air yet as grounded as carbon fiber.

## Colors

The palette is anchored in **Midnight Black** and **Deep Charcoal** to provide a void-like canvas that allows imagery to pop with cinematic intensity. 

- **Warm Gold (#D4AF37)**: Reserved for moments of high importance, interactive calls to action, and brand iconography. It represents the sun's peak glow.
- **Sunset Orange (#FF8C00)**: Used sparingly as an accent for "Golden Hour" highlights, active states, or subtle gradients that mimic the horizon line.
- **Surface Treatments**: Surfaces utilize semi-transparent blacks with subtle "Golden Hour" glows at the edges to simulate light hitting a glass edge.

## Typography

The typography system relies on the tension between the classical elegance of **Playfair Display** and the utilitarian precision of **Inter**.

- **Headlines**: Use Playfair Display for all storytelling and high-level navigation. Tight tracking on large headers creates a sophisticated, editorial feel.
- **Body**: Inter provides a clean, neutral counter-balance, ensuring legibility against complex photographic backgrounds.
- **Technical Accents**: Use the `label-caps` style for metadata, navigation categories, and small utility text. The wide letter spacing (0.2em) mimics technical instrumentation and adds a "SpaceX" precision vibe.

## Layout & Spacing

This design system uses a **Fixed Grid** philosophy for content to maintain elite editorial control, set within a **Fluid Canvas** for background imagery and glass layers.

- **Grid**: A 12-column grid with generous 24px gutters.
- **Rhythm**: Spacing follows an 8px base unit. Section gaps are intentionally large (120px+) to force the user to slow down and appreciate the visual pacing, similar to a high-end tasting menu.
- **Responsiveness**: On mobile, margins tighten to 20px, and large display fonts scale down significantly to maintain the "luxury magazine" proportions without overflowing the viewport.

## Elevation & Depth

Depth is achieved through **Optical Layering** rather than traditional shadows.

1.  **The Void (Level 0)**: The base midnight black background.
2.  **Atmospheric Glass (Level 1)**: Large containers for content use a `backdrop-filter: blur(20px)` with a 5% white opacity. This creates the "SpaceX window" effect.
3.  **Floating Elements (Level 2)**: Cards or modals use a slightly higher opacity (8%) and a subtle 1px border stroke with a linear gradient (Gold to Transparent) to simulate light catching the edge of a glass pane.
4.  **Golden Glow**: Instead of drop shadows, active elements may have a faint, ultra-diffused outer glow in gold (#D4AF37 at 10% opacity) to signify interaction.

## Shapes

The shape language is **Soft (0.25rem)**, reflecting the precision of machined materials. Large-scale imagery and primary containers use sharp corners or very small radii to maintain a professional, architectural feel. 

- **Buttons**: Use `rounded-lg` (0.5rem) to feel approachable yet precise.
- **Imagery**: Stays sharp (0px) to maximize the cinematic impact and grid alignment.
- **Interactive States**: Use micro-interactions where shapes might slightly expand or "breath" with slow, eased transitions.

## Components

### Buttons
- **Primary**: Solid Gold (#D4AF37) with Midnight Black text. No shadow, but a slight inner glow on hover.
- **Ghost**: A 1px gold border with white text. On hover, the background fills with a 5% gold tint.

### Cards & Containers
Containers must always use the glassmorphic treatment. Borders are 1px, using a top-down gradient from `rgba(255,255,255,0.2)` to `transparent`.

### Inputs & Selection
- **Fields**: Minimalist underline or 2-sided border only. Typography remains Inter.
- **Active State**: The underline transitions from charcoal to a sunset orange gradient.

### Lists & Menus
Menu items use Playfair Display for the item name and Inter for the description/price. Use large vertical padding (24px+) between items to emphasize the "SpaceX-meets-NatGeo" focus on individual details.

### Imagery
Images should be high-contrast, featuring deep blacks and warm, golden lighting. Use a subtle grain overlay across the entire UI to enhance the cinematic, film-like quality.
