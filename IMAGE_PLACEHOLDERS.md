# PLAGUE Website - Image Placeholders

This document lists all the placeholder images that need to be replaced with actual figures from the paper.

## Placeholder Images to Replace

### 1. **teaser.png** (1200x600px recommended)
- **Location:** `static/images/teaser.png`
- **Used in:** Hero section (top of page)
- **Description:** Main framework overview diagram showing the PLAGUE architecture and three phases (Primer, Planner, Finisher)
- **Suggestion:** Use the main figure from the paper that shows the complete system architecture

### 2. **results_asr.png** (800x500px recommended)
- **Location:** `static/images/results_asr.png`
- **Used in:** Key Results section
- **Description:** Bar chart or graph comparing attack success rates across different LLMs
- **Suggestion:** Create a clean bar chart showing PLAGUE vs baseline methods across different models

### 3. **ablation.png** (800x500px recommended)
- **Location:** `static/images/ablation.png`
- **Used in:** Ablation Study section
- **Description:** Graph showing the contribution of each phase when removed
- **Suggestion:** Use ablation study results from the paper

### 4. **example_1.png** (600x400px recommended)
- **Location:** `static/images/example_1.png`
- **Used in:** Qualitative Examples section
- **Description:** Example conversation showing gradual context building
- **Suggestion:** Screenshot or formatted text showing a multi-turn conversation from the Primer phase

### 5. **example_2.png** (600x400px recommended)
- **Location:** `static/images/example_2.png`
- **Used in:** Qualitative Examples section
- **Description:** Example conversation showing strategic planning
- **Suggestion:** Screenshot showing the Planner phase in action

### 6. **example_3.png** (600x400px recommended)
- **Location:** `static/images/example_3.png`
- **Used in:** Qualitative Examples section
- **Description:** Example showing multi-turn evolution
- **Suggestion:** Screenshot showing how attacks evolve over multiple turns

### 7. **example_4.png** (600x400px recommended)
- **Location:** `static/images/example_4.png`
- **Used in:** Qualitative Examples section
- **Description:** Example showing successful jailbreak
- **Suggestion:** Screenshot showing the Finisher phase and successful attack

## Additional Content to Update

### Performance Table
The HTML contains a comparison table with placeholder numbers. Update these values in `index.html` around line 224-258:

```html
<table class="table is-bordered is-striped is-fullwidth">
  <!-- Update these values with actual results from paper -->
</table>
```

Current placeholder values:
- GPT-4o: 73.2% (PLAGUE), 24.1% (Single-Turn), 45.6% (Multi-Turn)
- Claude Opus 4.1: 67.3% (PLAGUE), 18.9% (Single-Turn), 41.2% (Multi-Turn)
- OpenAI o3: 81.4% (PLAGUE), 31.5% (Single-Turn), 52.8% (Multi-Turn)
- Gemini 2.0 Pro: 69.8% (PLAGUE), 22.3% (Single-Turn), 43.7% (Multi-Turn)

## Image Format Recommendations

- **Format:** PNG or JPEG (PNG preferred for diagrams with text)
- **Resolution:** High DPI for crisp display on retina screens
- **Size:** Keep file sizes reasonable (< 500KB per image when possible)
- **Style:** Consistent color scheme and typography across all figures
- **Text:** Ensure all text in images is legible at display size

## How to Replace Images

1. Export figures from your paper at appropriate resolution
2. Name them according to the filenames above
3. Place them in `static/images/` directory
4. Refresh the browser to see changes

## Optional Enhancements

Consider adding:
- A video demo (can be embedded in the commented-out video section)
- Additional qualitative examples
- Interactive visualizations or demos
- Links to dataset and code (when available)

## After Replacing Images

Once you've replaced all placeholder images:
- Test the website locally to ensure all images load correctly
- Check mobile responsiveness
- Verify that image captions accurately describe the figures
- Delete this README file or keep it for reference
