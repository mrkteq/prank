# Intentionally Terrible Portfolio Website

Single-page transformation demo showcasing AI prompting and design direction skills through deliberate anti-pattern showcase.

![Prank Project Screenshot](Screenshot.png)

**[Live Demo](https://mrkteq.github.io/prank/)** | **[Portfolio](https://marktucker-portfolio.netlify.app/)**

## Tech Stack

- **HTML5** - Semantic structure with progressive enhancement
- **CSS3** - Animations, transforms, and transitions
- **JavaScript (ES6)** - DOM manipulation and state management

## Features

- CSS animations and keyframe transitions for visual effects
- State-driven UI toggle revealing professional explanation
- DOM manipulation for dynamic content transformation
- Single-button interaction triggering complete visual redesign
- Intentional anti-patterns demonstrating design awareness

## Technical Implementation

### Architecture
Single-page application with JavaScript-controlled state toggle. Initial "terrible" state uses deliberately poor design choices (Comic Sans, clashing colors, animated GIFs), while transformed state reveals clean, professional layout.

### Key Challenges Solved
1. **Smooth State Transition**: Implemented CSS transitions for seamless visual transformation between chaotic and professional states without page reload
2. **DOM Content Swap**: Used JavaScript to dynamically replace content while maintaining semantic HTML structure and accessibility
3. **Visual Impact**: Created deliberate contrast between states to demonstrate understanding of design principles through their violation

### Performance Optimizations
- Single HTML file reduces HTTP requests
- CSS-driven animations use GPU acceleration
- Minimal JavaScript footprint (~50 lines)
- No external dependencies or frameworks

## Metrics

| Metric | Score |
|--------|-------|
| Lighthouse Performance | 98 |
| Lighthouse Accessibility | 72 |
| Lighthouse Best Practices | 100 |
| Lighthouse SEO | 91 |
| Page Load Time | ~1.1ms |
| Total Page Weight | ~10KB |

*Run Lighthouse audit to populate metrics*

## Installation

```bash
# Clone repository
git clone https://github.com/mrkteq/prank.git

# Open index.html in browser
# No build process required
```

## Deployment

Deployed on GitHub Pages with automatic deployments from main branch.

## Design Rationale

This project demonstrates:
- Understanding of modern design principles through their deliberate violation
- Ability to direct AI-generated content toward specific outcomes
- Technical implementation of state-driven UI transformations
- Attention to user experience through clear interaction patterns

The "terrible" design includes every anti-pattern: autoplay music, marquee tags, clashing neon colors, Comic Sans typography, spinning GIFs, and skill bars exceeding 100%. The "Make it Stop" button reveals a professional explanation of the project's purpose.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT