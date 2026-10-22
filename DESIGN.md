---
name: My Design System
colors:
  surface: '#f6fbef'
  surface-dim: '#d6dcd0'
  surface-bright: '#f6fbef'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f5e9'
  surface-container: '#eaf0e4'
  surface-container-high: '#e5eade'
  surface-container-highest: '#dfe4d8'
  on-surface: '#181d16'
  on-surface-variant: '#404a3c'
  inverse-surface: '#2c322a'
  inverse-on-surface: '#edf3e6'
  outline: '#707a6b'
  outline-variant: '#bfcab8'
  surface-tint: '#0a6e14'
  primary: '#005309'
  on-primary: '#ffffff'
  primary-container: '#0a6e14'
  on-primary-container: '#91ee84'
  inverse-primary: '#80db74'
  secondary: '#106d2e'
  on-secondary: '#ffffff'
  secondary-container: '#9cf4a4'
  on-secondary-container: '#187132'
  tertiary: '#3c4a3d'
  on-tertiary: '#ffffff'
  tertiary-container: '#546254'
  on-tertiary-container: '#cdddcb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#9bf88d'
  primary-fixed-dim: '#80db74'
  on-primary-fixed: '#002202'
  on-primary-fixed-variant: '#005309'
  secondary-fixed: '#9ff6a7'
  secondary-fixed-dim: '#83da8d'
  on-secondary-fixed: '#002108'
  on-secondary-fixed-variant: '#00531f'
  tertiary-fixed: '#d7e7d5'
  tertiary-fixed-dim: '#bbcbba'
  on-tertiary-fixed: '#121e14'
  on-tertiary-fixed-variant: '#3c4a3d'
  background: '#f6fbef'
  on-background: '#181d16'
  surface-variant: '#dfe4d8'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

# Design System Document

## Brand & Style
The design system adopts a **Corporate / Modern** style, emphasizing reliability, balance, and professionalism. The interface utilizes the **Inter** font family for a clean, highly legible, and contemporary aesthetic across all scales.

## Colors
The color palette operates in **light** mode:
- **Primary**: `#0a6e14`
- **Secondary**: `#6dc278`
- **Tertiary**: `#e2f2e0`

## Typography
- **Font Family**: Inter (Headline, Body, Label)

## Layout & Spacing
Standard spacing scale implemented with a 1rem gutter and 1.5rem margin rhythm.

## Elevation & Depth
Clean tonal layers and subtle outlines are used to create structured visual hierarchy.

## Shapes
Rounded geometry (`roundedness: 2`) with 0.5rem standard radiuses applied to interactive elements.

## Components
Consistent styling applied to buttons, cards, inputs, and chips following the defined color and shape tokens.