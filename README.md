# Film Scoring Composition Spec Kit Preset

A Spec Kit preset that adapts the standard **spec + plan + tasks** workflow to film scoring, orchestration, and musical composition.

Instead of treating a project as software to be implemented, this preset treats it as **music evolving over time**.

## Core Concept Mapping

This preset reinterprets Spec Kit concepts into a composition-first workflow:

| Spec Kit Concept | In Software            | In Film Scoring Composition                                       |
| ---------------- | ---------------------- | ----------------------------------------------------------------- |
| **Feature**      | Functional capability  | Musical building block (motif, texture, gesture, instrument role) |
| **Spec**         | Feature specification  | Cue brief (intent, emotion, constraints)                          |
| **Plan**         | Technical architecture | Musical structure (timeline, sections, development)               |
| **Tasks**        | Implementation steps   | Composition, orchestration, and production steps                  |

## Features: Musical Building Blocks

In this preset, features become **musical building blocks**:

* motifs and thematic ideas
* textures (pads, ostinatos, rhythmic layers)
* orchestral roles (strings = emotion, brass = impact, etc.)
* harmonic language and tonal centers

## Specs: Cue Brief (Intent)

In this preset, a spec becomes a **cue brief**:

* emotional intent (what should the audience feel?)
* dramatic function (what does the music do in the scene?)
* constraints (duration, instrumentation, assignment requirements)
* success criteria (rubric, clarity, musicality)

## Plans: Structure Over Time

In composition, this becomes **structure and form**:

* timeline (sections, cues, transitions)
* development of material (introduction → build → climax → resolution)
* orchestration evolution
* energy and density curves

## Tasks: Composition & Production Work

In this preset, tasks become **practical composing actions**:

* sketch motifs and textures
* define sections and pacing
* compose each part of the cue
* orchestrate instruments
* build the mockup (Logic, libraries, CC shaping)
* balance and mix
* export deliverables

## Workflow Summary

The workflow becomes:

1. **Spec (Cue Brief)**
   Define intent, emotion, constraints, and success criteria

2. **Plan (Structure)**
   Design the timeline, sections, and development

3. **Tasks (Execution)**
   Compose, orchestrate, produce, and deliver

4. **Checklist (Validation)**
   Ensure musical quality, technical correctness, and rubric alignment

## Philosophy

This preset is designed to:

* support creative flow instead of interrupting it
* make musical intent explicit
* reduce friction in starting and finishing work
* create a repeatable workflow for both study and professional scoring

## Best Use Cases

* film scoring cues
* orchestration studies
* personal composition projects
* collaboration with directors / storytellers

## Install locally
```bash
specify preset add --dev /path/to/spec-kit-preset-film-scoring-composition
```

## Install from release
```bash
specify preset add --from https://github.com/pjorquera/spec-kit-preset-film-scoring-composition/archive/refs/tags/v0.1.0.zip
```

## Test resolution
```bash
specify preset resolve spec-template
specify preset info film-scoring-composition
specify preset list
```

## License

```text
MIT License

Copyright (c) 2026 Pedro Jorquera

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```