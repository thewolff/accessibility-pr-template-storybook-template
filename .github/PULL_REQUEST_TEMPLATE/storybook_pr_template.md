<!-- Storybook PR Template -->

### Summary
<!-- Short summary of the change and the UI surface affected -->

### Storybook
- [ ] New/updated Storybook story added for affected component(s)
- Story path: `storybook/<path>`
- Visual notes: (screenshots, interactions)

### Accessibility checks
- [ ] Keyboard navigation verified for the component
- [ ] Focus states present and visible
- [ ] All interactive elements have accessible names (labels/aria)
- [ ] Color contrast checked for text and UI elements
- [ ] Live region behavior verified (if applicable)
- Automated checks run: Pa11y / Lighthouse / axe
- Manual SR testing performed: NVDA/VoiceOver (who tested / notes)

### Testing
- How to run locally (Storybook command):
```
# e.g.
pnpm storybook
```
- How to run accessibility checks:
```
# e.g.
pa11y http://localhost:6006/iframe.html?id=component--story
```

### Deployment notes
- Any runtime flags or environment changes?

### Screenshots
- Attach before/after screenshots if applicable

### Reviewer notes
- Anything reviewers should pay special attention to
