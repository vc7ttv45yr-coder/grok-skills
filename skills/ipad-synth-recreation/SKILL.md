---
name: ipad-synth-recreation
description: Specialized assistant for recreating synthesizer sounds on iPad using Logic Pro Alchemy, Buttersynth and related apps. Trigger on requests for synth patch recipes, sound matching from audio analysis, iPad sound design walkthroughs for glitch hop dubstep hyperpop or similar genres, or when user pastes audio-analyzer JSON metrics.
---

# iPad Synth Recreation

## Overview

This skill provides detailed, ready-to-use procedures for translating audio-analyzer MIR output (spectral centroid, harmonic/percussive ratios, etc.) into practical iPad synth patches in Logic Pro (Alchemy), Buttersynth, and compatible apps. It includes feature mappings, genre-specific recipes, tap-by-tap walkthroughs, and customization workflows.

## Trigger & Usage Guidelines

- Use when user wants a custom patch for a specific sound/track (provide JSON metrics or description).
- Combine with audio-analyzer and music-production-assistant skills.
- Always prioritize ear-matching and iterative tweaking; reference the full guide in references/ for details.

## Core Procedures

1. **Identify Synth Type**
   - High spectral_centroid_hz (>2800): Bright leads/supersaw.
   - High harmonic_ratio + low percussive: Sustained pads.
   - High percussive/onsets: Plucky/arpeggiated.
   - Genre-specific: Use Dubstep, Glitch Hop, Hyperpop recipes.

2. **Apply Mappings**
   - Brightness (centroid) → Filter cutoff & waveform choice.
   - Sustain → Envelope A/R + slow LFO.
   - Rhythmic → Synced LFO/step modulation.

3. **Build Patch**
   - Load starting template from references.
   - Follow walkthroughs for Alchemy/Buttersynth.
   - Fine-tune with original audio reference.

## References
- Full guide and templates: references/iPad_Synth_Recreation_Reference_Guide.md
- Walkthroughs and genre recipes are embedded in the reference file.

## Advanced Integration
- Export short loops to Alchemy for spectral import.
- Map parameters to MIDI controllers (Tempopad16, Launchpad MK3).
- Layer with Koala/Drambo/AUM for complex textures.
- Generate visual diagrams or PDF updates as needed.