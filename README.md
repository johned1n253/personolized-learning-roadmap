# Personalized Learning Roadmap

> Everyone gets the same learning path → most people abandon it → nobody knows whether anything was learned.

An AI system that creates **personalized learning paths** through real technical content (roadmap.humblebee.ai), with level assessment, adaptive checkpoints, and progress tracking.

## Problem

High-quality free learning material is abundant, but completion is not.  
Identical paths for beginners and experienced engineers cause two failure modes:

- Experienced learners quit out of boredom.
- Beginners quit out of overwhelm.
- No verification of understanding → false sense of progress.

This is a core business problem for learning platforms, corporate training teams, and education providers.

## Solution

1. **Onboarding** – Coding background + end goal (open-ended).
2. **Level Inference** – AI assesses current level and explains its reasoning (learner can correct it).
3. **Personalized Path** – Ordered route through real content. Skipped material is explicitly marked and justified.
4. **Checkpoints** – Questions and coding problems generated from the actual content of each section.
5. **Adaptive Progress** – Failed checkpoints block or replan the remaining path.
6. **Different paths for different learners** – Demonstrably different routes for e.g. experienced backend → CV vs complete beginner → CV.

## Target Buyers

- Learning platforms / content publishers (completion & retention)
- Companies running internal technical upskilling
- Education providers serving students with uneven backgrounds

## Tech Stack (planned)

- Frontend: (TBD – React / Next.js / Gradio / Streamlit)
- Backend & AI: Python, LLMs for assessment + path generation + checkpoint creation
- Content source: roadmap.humblebee.ai (CC BY-NC-SA 4.0)
- Hosting: Hugging Face Spaces / Vercel / etc.

## Team

| Name | Role |
|------|------|
| Umaraliev Makhmudjon | Project Manager |
| Abdulkhaev Akbarjon | Marketing & Research |
| Jalilov Jakhongir Zukhriddin ugli | Research |
| Li Mikhail | Backend / AI Engineer |
| Imetov Daniiar | Frontend / Full-stack |
| Chagai Vladimir | AI / Data Engineer |

## Licence & Attribution

Content is based on [roadmap.humblebee.ai](https://roadmap.humblebee.ai) licensed under **CC BY-NC-SA 4.0**.  
We will properly attribute the original work and comply with share-alike and non-commercial terms.

## Status

- [x] Team formed & roles assigned
- [x] Repository created
- [ ] Baseline features (onboarding, level inference, path generation)
- [ ] Target features (checkpoints, adaptive path, web UI, real learner testing)
- [ ] Stretch goals

## Demo Script (planned)

1. Business case – cost of low completion
2. Onboard experienced backend engineer → Computer Vision → show personalized path + skips
3. Onboard complete beginner with same goal → show different path
4. Fail a checkpoint deliberately → path adapts
5. Results from real learner testing
6. Value to the buyer

---

**Repository**: https://github.com/mishalilia/personalized-roadmap  
