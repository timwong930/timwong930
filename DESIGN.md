---
name: Tim Wong GitHub Profile
description: Warm editorial portfolio system for a curious maker
colors:
  light-canvas: "#ffffff"
  light-muted-surface: "#f6f8fa"
  light-ink: "#24292f"
  light-body: "#59636e"
  light-rule: "#d1d9e0"
  light-olive: "#4d6548"
  light-rust: "#895640"
  dark-canvas: "#0d1117"
  dark-muted-surface: "#161b22"
  dark-ink: "#e6edf3"
  dark-body: "#a1aab4"
  dark-rule: "#30363d"
  dark-olive: "#b8ceb0"
  dark-rust: "#d9a389"
typography:
  display:
    fontFamily: "Georgia, Times New Roman, serif"
    fontSize: "54px"
    fontWeight: 700
  body:
    fontFamily: "Arial, Helvetica, sans-serif"
    fontSize: "19px"
    fontWeight: 400
rounded:
  panel: "5px"
  rule: "2px"
---

## Overview

This GitHub profile should feel like a maker's field notebook: curious, warm, considered, and useful. It is a portfolio of practical projects, not an AI brand or a technology product landing page. Preserve the first-person story of questioning problems and building tools to understand and improve them.

## Colors

Blend into GitHub's light and dark defaults, using white and near-black canvases. Olive is a quiet accent and rust is reserved for small labels. Avoid colored slabs, bright gradients, glowing nodes, and decorative dashboard cards. Explicit light and dark SVG assets ensure contrast and theme parity.

## Typography

Use Georgia for authored headlines and section graphics, with a sturdy Arial/Helvetica stack for labels, annotations, and supporting text. Let words carry the hierarchy rather than gradient fills, pills, or excessive all-caps.

## Layout

The GitHub README uses native Markdown for legible body text and project links. The four SVG systems are the hero banner, problem-solving sequence, current interests, and closing motto. Desktop images are 1080 to 1200 units wide; mobile-specific variants switch at 640px through HTML picture sources, with parallel sources for light/dark schemes.

## Elevation & Depth

Flat layered surfaces and hairline rules only. No shadows or halos. Contrast must support reading against cream and deep olive backgrounds.

## Shapes

Minimal squared or slightly softened edges, fine dividers, and the occasional annotation mark. Avoid equal-size technology cards and ornamental data-network diagrams.

## Components

Each visual ships in desktop/mobile and light/dark variants. The exploration panel stays entirely static. The header, process, and footer use native SVG SMIL for visible motion, with separately rendered static variants selected via prefers-reduced-motion picture sources. Animated components follow existing rules, dots, or the process sequence, never floating freely across the exploration panel. Maintain GitHub-aligned backgrounds and readable content even when motion cannot play.

## Do's and Don'ts

- Keep the project descriptions factual and in the author's first-person voice.
- Favor movement that represents iteration, progress, or research.
- Keep SVG images readable on phone widths.
- Do not reintroduce animated blobs, bright gradients, glowing networks, or flashy badges.
- Avoid em dashes in profile-facing copy.
- Do not feature projects that are still private unless the author explicitly requests it.
