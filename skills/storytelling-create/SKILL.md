---
name: storytelling-create
description: Create presentation materials from an existing storytelling plan. Use when the user has an audience/message/story plan and wants to turn it into slide structure, style choices, takeaway titles, slide wording, data-slide flow, graph takeaways, image or diagram choices, Big Idea callbacks, horizontal logic, navigation, deck readiness checks, or appendix support without losing the story.
---

# Storytelling Create

Use this skill when the user is moving from a planned communication into presentation materials.

This skill starts with the **Create** section of *Storytelling with You*. It assumes `storytelling-plan` has already handled audience, message, storyboard, and story shape. If those inputs are missing, ask briefly or send the user back to planning before creating slides.

Current coverage:

- **Chapter 5: Set the style & structure**
  - style constraints,
  - slide master / template choices,
  - deck skeleton,
  - takeaway titles,
  - horizontal logic,
  - navigation scheme,
  - and appendix support.
- **Chapter 6: Say it with words**
  - presentation titles,
  - words as slide content,
  - speaker notes vs slide text,
  - attention contracts,
  - Big Idea repetition,
  - and closing language.
- **Chapter 7: Show data in graphs**
  - data inclusion decisions,
  - graph takeaway sentences,
  - chart form by function,
  - graph decluttering and focus,
  - progressive graph builds,
  - and data appendix support.
- **Chapter 8: Illustrate with images**
  - image inclusion decisions,
  - photograph / illustration / diagram / map choices,
  - image-message pairing,
  - visual navigation schemes,
  - live vs virtual image use,
  - diagram decluttering and focus,
  - and custom image support.

Read:

- `references/style-structure.md` for Chapter 5 creation guidance.
- `references/words.md` when writing presentation titles, slide text, speaker notes, Big Idea callbacks, or text-heavy slide treatments.
- `references/graphs.md` when creating data slides, choosing chart forms, writing graph takeaways, sequencing graph builds, or deciding whether data belongs in the main story or appendix.
- `references/images.md` when creating image-heavy slides, choosing between photographs / illustrations / diagrams / maps, using images for navigation or memory, adapting visuals for live vs virtual delivery, or deciding whether an image belongs at all.
- `references/quality-gate.md` when the deck skeleton and content treatment are drafted and you need to test readiness before production or polish.

## Inputs to collect

Collect or infer:

- audience,
- desired action,
- Big Idea,
- story path or narrative arc,
- main story vs appendix / proof split,
- existing storyboard or deck skeleton,
- brand, template, or slideware constraints,
- credibility concerns,
- phrases the audience should remember or reuse,
- places where text is needed for the presenter rather than the audience,
- data, metrics, tables, or analysis that might need to appear,
- the point each graph or data slide should make,
- whether the audience needs analysis detail or only the implication,
- existing chart, dashboard, or table constraints,
- products, places, people, processes, prototypes, or scenarios the audience may need to see,
- available image assets, brand imagery, photography, illustrations, diagrams, icons, or maps,
- whether images need to set tone, aid memory, clarify structure, or provide navigation,
- image sourcing, copyright, attribution, or confidentiality constraints,
- and whether the output is for live presentation or standalone reading.

Ask only for missing details that materially change the structure. If the user has no audience, action, Big Idea, or story path, pause and use `storytelling-plan` first.

## Default workflow

### 1) Check the plan

Confirm the minimum plan exists:

- who the presentation is for,
- what action or decision should happen,
- what the Big Idea is,
- what story path has been chosen,
- and what detail belongs outside the main story.

Do not re-plan from scratch unless the existing plan is weak or absent.

### 2) Set style constraints

Use `references/style-structure.md`.

Decide:

- whether to use an existing template,
- what visual tone fits the topic and audience,
- what brand constraints must be respected,
- what layout choices support the main takeaway,
- and what risks could distract from the message.

Keep style decisions practical. The goal is visual support, not decoration.

### 3) Build the deck skeleton

Create the low-fidelity deck inside the slide structure before building content.

Include:

- title slide,
- rough section structure,
- slide titles,
- divider or navigation slides if useful,
- appendix / proof sections,
- and notes for details that should not enter the main slide content yet.

### 4) Write takeaway titles

Prefer takeaway titles over topic labels.

Weak:

- "Customer preferences"
- "Cost increase"
- "Packaging test"

Stronger:

- "Customers prefer the original mix"
- "Macadamia costs threaten margin"
- "Packaging changes alone will not solve the problem"

Each slide title should answer: "So what?"

### 5) Design words on slides

Use `references/words.md`.

For title slides, slide titles, text-heavy slides, Big Idea slides, quotes, and closing slides, decide:

- what the words should make the audience do now,
- what belongs on the slide surface,
- what belongs in speaker notes,
- where the Big Idea should appear or return,
- and which phrase should be memorable and retellable.

Do not let slide text solve the presenter's memory problem at the audience's attention cost.

### 6) Design data slides and graph flow

Use `references/graphs.md` when data appears in the presentation.

For each data slide, decide:

- whether the data belongs in the main story,
- what takeaway sentence the graph should make clear,
- what graph form best serves that function,
- what should be removed, muted, or emphasized,
- whether the graph should be built progressively,
- and what data detail belongs in the appendix instead.

Do not present raw analysis just because it exists. Use data to support the story, not to prove that work happened.

### 7) Design image and diagram support

Use `references/images.md` when images, photographs, illustrations, diagrams, or maps appear in the presentation.

For each visual, decide:

- whether the audience needs to see it,
- what message, feeling, memory hook, or orientation job it serves,
- whether a photograph, illustration, diagram, map, or repeated navigation image is the right form,
- what should be cropped, removed, muted, or emphasized,
- whether delivery mode changes the treatment,
- and what image detail belongs in the appendix, notes, or production task list instead.

Do not use images as filler. Use them to help the audience see, understand, feel, remember, or navigate the story.

### 8) Test horizontal logic

Read only the titles.

Check whether they show:

- context,
- tension,
- evidence,
- implication,
- action,
- and a coherent path from beginning to end.

If the title-only version does not work, fix the structure before building slide content.

### 9) Decide navigation

For longer or multi-section presentations, create a navigation scheme.

Use it to:

- set expectations near the beginning,
- show where the audience is during transitions,
- make section changes visible,
- and keep the presenter on track.

Skip navigation if the presentation is short and the title sequence already gives enough orientation.

### 10) Map appendix support

Use the appendix as a tool for credibility and detail management.

Move detail out of the main presentation when it:

- supports trust but slows the story,
- answers likely skeptical questions,
- shows method, caveats, or backup analysis,
- or matters to only a subset of the audience.

The appendix is not a dumping ground. It should be organized enough to use during discussion.

### 11) Run the deck readiness test

Use `references/quality-gate.md` after the structure and content treatments are drafted.

Check:

- story integrity,
- desired audience action,
- horizontal logic,
- slide-level attention contracts,
- evidence burden,
- visual purpose,
- delivery fit,
- and appendix readiness.

Do not move into polish or production if the test reveals structural uncertainty.

## Default output

Unless the user asks otherwise, produce:

1. `Plan check`
2. `Style constraints`
3. `Deck skeleton`
4. `Takeaway title sequence`
5. `Word design`
6. `Data-slide / graph design`
7. `Image / diagram design`
8. `Horizontal logic test`
9. `Navigation choice`
10. `Appendix map`
11. `Deck readiness test`
12. `Risks / unresolved choices`
13. `Next production move`

## Behavior rules

- Start from the existing story plan, not from slide design.
- Do not create final slide content before the skeleton is tested.
- Treat slides for live presentation differently from standalone documents.
- Keep the deck low-fidelity until structure is defensible.
- Use takeaway titles as argument steps.
- Separate speaker memory from audience attention.
- Treat text slides as attention contracts: decide whether the audience should read, scan, listen, pause, discuss, or remember.
- Repeat the Big Idea only when intervening context makes the return mean more.
- Treat the same sentence differently depending on placement: before evidence it frames; after evidence it concludes.
- Do not include data just because it exists.
- Write the graph takeaway sentence before designing or polishing a graph.
- Choose graph form by function, not novelty.
- Prefer familiar line and bar graphs unless another form earns its interpretation cost.
- Declutter graphs to reduce effort, then add focus to create meaning.
- Build dense or unfamiliar graphs step by step when audience comprehension depends on sequence.
- Use raw tables in the main story only when the table itself is the point; otherwise move them to appendix or backup material.
- Do not add images because a slide has empty space.
- Choose photographs, illustrations, diagrams, maps, or navigation images by function.
- Pair each image with the message, feeling, memory hook, or orientation job it should support.
- Treat diagrams like graphs: remove clutter first, then add focus.
- Adjust visual treatment for live, virtual, or standalone delivery.
- Use horizontal logic as the deck-level structure test.
- Use the appendix to preserve credibility without overloading the main path.
- Run a readiness test before moving from low-fidelity creation into polish or production.
- If the work drifts back into audience/message/story planning, switch to `storytelling-plan`.
