# Developer Guide: Adding New Source Types

This guide shows how to add new source types to the Citation Builder without rebuilding the entire file.

## Quick Overview
To add a new source type, you need to update 3 sections in `citation-builder.html`:
1. Add a new tab button
2. Add a new form section
3. Add a new generator function

---

## Step 1: Add Tab Button

**Location:** Find the `<div class="tabs">` section (around line 100)

**Add this line** after the last tab:
```html
<div class="tab" data-tab="SOURCETYPE">Source Type Name</div>
