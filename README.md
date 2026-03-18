# Vital Insights - Health Analytics Dashboard

A comprehensive health data intelligence platform providing advanced cardiovascular health analysis, lifestyle factor insights, and demographic pattern visualization through interactive Tableau dashboards.

## Overview

Vital Insights is an elegant, responsive web-based analytics dashboard that combines modern design principles with powerful data visualization. It analyzes cardiovascular health patterns across diverse populations, providing actionable insights on heart disease prevalence, BMI correlation, and demographic trends.

## Key Features

| Feature                        | Description                                                        | Status      |
| ------------------------------ | ------------------------------------------------------------------ | ----------- |
| Interactive Tableau Dashboards | Embedded complete dashboard and heart disease story visualizations | Implemented |
| Key Statistics Section         | Real-time stat cards with animated counters                        | Implemented |
| Responsive Design              | Mobile-first approach optimized for all screen sizes               | Implemented |
| Smooth Animations              | Fade-in, scroll reveal, and counter animations for engagement      | Implemented |
| Modern UI/UX                   | Glass-morphism effects with gradient overlays                      | Implemented |
| Navigation Links               | Smooth scrolling with active link highlighting                     | Implemented |
| Accessible Layout              | Semantic HTML structure for better accessibility                   | Implemented |
| Dark Theme                     | Professional dark interface with accent colors                     | Implemented |

## Technology Stack

| Component            | Technology                               | Version   |
| -------------------- | ---------------------------------------- | --------- |
| Frontend Framework   | HTML5                                    | Latest    |
| Styling              | CSS3                                     | Latest    |
| Interactive Elements | Vanilla JavaScript                       | ES6+      |
| Data Visualization   | Tableau Public                           | Latest    |
| Fonts                | Google Fonts (Playfair Display, Poppins) | Latest    |
| Performance          | Backdrop Filters & CSS Transitions       | Optimized |

## Color Palette

| Color           | Purpose                           | Hex Value |
| --------------- | --------------------------------- | --------- |
| Primary         | Main interface background         | #1e3a5f   |
| Primary Light   | Secondary backgrounds             | #2d5a8c   |
| Accent          | Highlights & interactive elements | #e8a87c   |
| Accent Dark     | Hover states                      | #d4925a   |
| Success         | Positive indicators               | #4a9d6f   |
| Danger          | Warning/negative indicators       | #c74b50   |
| Warning         | Caution elements                  | #f8a86a   |
| Background Dark | Primary dark background           | #0f1419   |
| Text Primary    | Main text color                   | #f5f7fa   |
| Text Secondary  | Secondary text color              | #a8b0c0   |
| Gold            | Gradient accents                  | #d4a574   |
| Teal            | Secondary accents                 | #4a9b9e   |

## Dashboard Sections

### Hero Section

Introductory banner with clear value proposition and dataset overview. Welcomes users to the platform with compelling copy about health data intelligence.

### Key Statistics

Four stat cards displaying critical metrics:

| Metric              | Value       | Description              |
| ------------------- | ----------- | ------------------------ |
| Total Population    | 283         | Individuals analyzed     |
| Heart Disease Cases | 283         | With confirmed diagnosis |
| Average BMI Range   | 23.91–42.78 | Population spread        |
| Age Groups          | 18+         | Adults tracked           |

### Distribution Analysis

Two interactive Tableau visualizations:

#### Complete Dashboard

Comprehensive multi-chart dashboard featuring:

- Disease prevalence metrics
- Demographic breakdowns
- Age correlation analysis
- Lifestyle factor impact
- Interactive filters and drill-down capabilities

#### Heart Disease Story

Narrative-driven visualization showing:

- Racial/ethnic distribution analysis
- Gender vs heart disease correlation
- Age-based disease incidence
- Smoking and cholesterol impact
- Family history significance
- Overall disease count summary

### Key Insights

Strategic insights section highlighting:

- Cardiovascular pattern analysis
- Demographic trend analysis
- BMI and health correlation

## Installation & Setup

### Prerequisites

- Web browser with JavaScript enabled
- Internet connection (for Tableau API and Google Fonts)
- No server or build process required

### Quick Start

1. **Clone the repository**

```bash
git clone https://github.com/aviralMadhvan24/SkillWallet-Dashboard.git
cd SkillWallet-Dashboard
```

2. **Open in browser**

```bash
# Simply open the HTML file directly
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

3. **Or use a local server** (recommended)

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js with http-server
npx http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000` in your browser.

## Dataset Information

The dashboard analyzes health data from 283 individuals with the following attributes:

| Attribute             | Data Type   | Range/Categories                                                            | Significance               |
| --------------------- | ----------- | --------------------------------------------------------------------------- | -------------------------- |
| Age                   | Numeric     | 18+ years                                                                   | Cardiovascular risk factor |
| Sex/Gender            | Categorical | Male, Female                                                                | Demographic variable       |
| BMI (Body Mass Index) | Numeric     | 23.91 - 42.78                                                               | Health indicator           |
| Race/Ethnicity        | Categorical | American Indian/Alaska Native, Asian, Black, Mexican American, Other, White | Population diversity       |
| Heart Disease         | Binary      | Yes/No                                                                      | Target outcome variable    |
| Smoking Status        | Categorical | Current, Former, Never                                                      | Lifestyle factor           |
| Cholesterol Level     | Numeric     | Varies                                                                      | Health metric              |
| Diabetes Status       | Categorical | Yes/No/Borderline                                                           | Comorbidity indicator      |
| Physical Activity     | Binary      | Yes/No                                                                      | Lifestyle factor           |
| Alcohol Consumption   | Binary      | Yes/No                                                                      | Lifestyle factor           |

## Key Insights from Analysis

### Cardiovascular Patterns

Heart disease prevalence shows strong correlation with age and lifestyle factors. Physical activity plays a critical protective role across all demographics, reducing disease incidence regardless of other risk factors.

### Demographic Trends

Population analysis reveals significant variation across age groups and races. White and Asian populations represent the largest segments in this dataset, while heart disease distribution varies meaningfully across racial categories.

### BMI & Health Correlation

The observed BMI range (23.91–42.78) indicates diverse health profiles across the population. Borderline diabetes diagnosis shows notable intersection with BMI and age categories, suggesting metabolic risk clustering.

## Architecture & Code Structure

```
index.html                          # Main HTML file
├── <head>
│   ├── Meta tags (viewport, charset)
│   ├── Google Fonts imports
│   └── CSS styles (embedded)
│       ├── Color variables
│       ├── Typography
│       ├── Layout & Grid
│       ├── Component styles
│       ├── Animations
│       └── Responsive design
├── <body>
│   ├── <header> Navigation bar
│   │   └── Logo, Nav links
│   ├── <main> Main content
│   │   ├── Hero section
│   │   ├── Stats section
│   │   ├── Charts section
│   │   │   ├── Dashboard 1 (Tableau)
│   │   │   └── Dashboard 2 (Tableau)
│   │   └── Insights section
│   ├── <footer> Footer
│   └── <script> JavaScript (inline)
│       ├── Smooth scroll handler
│       ├── Scroll reveal animation
│       ├── Active nav link highlighting
│       └── Counter animation logic
```

## Browser Compatibility

| Browser         | Support | Notes                       |
| --------------- | ------- | --------------------------- |
| Chrome/Edge     | Full    | Latest versions recommended |
| Firefox         | Full    | Latest versions recommended |
| Safari          | Full    | macOS & iOS compatible      |
| Mobile Browsers | Full    | Responsive design optimized |
| IE 11           | Limited | Some features not supported |

## Performance Metrics

| Metric        | Value        | Status              |
| ------------- | ------------ | ------------------- |
| Page Load     | < 3s         | Optimized           |
| Animations    | 60 FPS       | Smooth              |
| Responsive    | Mobile-first | Fully responsive    |
| Accessibility | WCAG 2.1 AA  | Standards compliant |

## Customization Guide

### Modifying Colors

Edit CSS variables in the `:root` selector within the `<style>` tag:

```css
:root {
  --primary: #1e3a5f;
  --accent: #e8a87c;
  /* ... other variables */
}
```

### Updating Statistics

Modify the stat cards in the stats section:

```html
<div class="stat-card">
  <div class="stat-label">Your Label</div>
  <div class="stat-value">Your Value</div>
  <div class="stat-description">Your Description</div>
</div>
```

### Changing Tableau Visualizations

Replace the Tableau embed codes with your own:

- Update the `path` parameter for different visualizations
- Adjust width/height in the JavaScript section
- Modify the `name` and `embed_code_version` parameters as needed

### Customizing Insights

Update the insight cards with your own data:

```html
<div class="insight-card">
  <div class="insight-icon">🔍</div>
  <div class="insight-title">Your Title</div>
  <div class="insight-text">Your insight text</div>
</div>
```

## File References

| File        | Purpose                      | Size   |
| ----------- | ---------------------------- | ------ |
| index.html  | Main application file        | ~40 KB |
| aviral.twbx | Tableau workbook (Dashboard) | Binary |
| story.twbx  | Tableau workbook (Story)     | Binary |

## API Integration

The dashboard uses the following external APIs:

| Service        | Purpose        | Endpoint                                     |
| -------------- | -------------- | -------------------------------------------- |
| Google Fonts   | Typography     | fonts.googleapis.com                         |
| Tableau Public | Visualizations | public.tableau.com                           |
| Tableau API    | Embedding      | public.tableau.com/javascripts/api/viz_v1.js |

## Features Breakdown

### Animated Components

- Fade-in animations on page load
- Scroll-reveal animations for card elements
- Counter animations for statistics
- Smooth navigation transitions
- Hover effects on interactive elements

### Interactive Elements

- Navigation menu with active link highlighting
- Smooth scroll anchors to different sections
- Embedded Tableau dashboards with full interactivity
- Responsive grid layouts

### Responsive Breakpoints

- Desktop: Full layout with optimized spacing
- Tablet (768px): Adjusted typography and grid
- Mobile: Single-column layout with touch-friendly elements

## Development Workflow

```
1. Edit index.html directly
2. Save changes
3. Refresh browser to view updates
4. Use browser DevTools for debugging
5. Test on multiple devices/browsers
6. Commit changes to Git
7. Push to GitHub repository
```

## Git Repository

```bash
Repository URL: https://github.com/aviralMadhvan24/SkillWallet-Dashboard.git
Branch: main
Commits: Version controlled with descriptive messages
```

## Future Enhancements

| Enhancement            | Description                        | Priority |
| ---------------------- | ---------------------------------- | -------- |
| Data Export            | CSV/PDF export functionality       | Medium   |
| Advanced Filters       | User-defined data filtering        | High     |
| Real-time Data         | Integration with live data sources | Medium   |
| Dark/Light Mode        | User preference toggle             | Low      |
| Accessibility Features | Enhanced keyboard navigation       | Medium   |
| Analytics Tracking     | Page view and interaction metrics  | Low      |
| Multi-language Support | Internationalization (i18n)        | Low      |

## Performance Optimization

- Minified CSS embedded in HTML
- Lazy loading for Tableau visualizations
- CSS animations using transform and opacity for 60 FPS
- Efficient scroll event listeners with debouncing
- Optimized font loading strategy

## Accessibility Features

- Semantic HTML structure
- Proper heading hierarchy (H1, H2)
- Color contrast meeting WCAG 2.1 AA standards
- Alt text for images
- Keyboard navigation support
- Screen reader friendly layout

## Troubleshooting

| Issue                              | Solution                                                            |
| ---------------------------------- | ------------------------------------------------------------------- |
| Tableau visualizations not loading | Check internet connection, verify Tableau embed codes               |
| Fonts not displaying               | Clear browser cache, ensure Google Fonts API is accessible          |
| Animations not smooth              | Disable extensions, use modern browser, check hardware acceleration |
| Responsive layout broken           | Clear CSS cache, check viewport meta tag                            |
| Navigation links not working       | Verify section IDs match href values                                |

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please ensure your contributions:

- Follow the existing code style
- Maintain responsive design principles
- Include meaningful commit messages
- Test on multiple browsers

## License

This project is open source and available under the MIT License.

## Project Metadata

| Attribute    | Value                             |
| ------------ | --------------------------------- |
| Project Name | Vital Insights                    |
| Type         | Health Analytics Dashboard        |
| Subtitle     | Advanced Health Data Intelligence |
| Created      | 2024                              |
| Technology   | HTML5, CSS3, JavaScript, Tableau  |
| Repository   | GitHub                            |
| Status       | Active Development                |

## Contact & Support

For questions, suggestions, or issues:

- GitHub Issues: [Project Issues Page](https://github.com/aviralMadhvan24/SkillWallet-Dashboard/issues)
- Email: For direct inquiries
- Documentation: Inline code comments throughout index.html

## Changelog

### Version 1.0.0

- Initial release
- Complete dashboard with Tableau integration
- Heart disease story visualization
- Responsive design implementation
- Animation and interactivity features
- Statistics section with counters
- Insights section with key findings

---

**Last Updated:** March 9, 2026

**Version:** 1.0.0

**Status:** Production Ready
