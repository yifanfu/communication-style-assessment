# Communication Style Assessment

A multilingual web application for assessing communication styles based on the Douglas & Douglas (1992) framework.

## Features

- **Multilingual Support**: Available in English, Chinese (Simplified), Portuguese, and Vietnamese
- **Interactive Assessment**: 12-question personality style questionnaire
- **Visual Results**: Color-coded quadrant system showing communication style preferences
- **Educational Content**: Detailed descriptions of each communication style
- **Responsive Design**: Works on desktop and mobile devices

## Communication Styles

The assessment categorizes individuals into four primary communication styles:

1. **Blue/Direct**: Task-oriented, fast-paced, assertive
2. **Red/Spirited**: People-oriented, fast-paced, expressive
3. **Yellow/Considerate**: People-oriented, steady-paced, supportive
4. **Green/Systematic**: Task-oriented, steady-paced, analytical

## Getting Started

### Local Development

1. Clone the repository
2. Open `index.html` in a web browser
3. No build process required - it's a static HTML application

### Deployment

This project is optimized for deployment on Cloudflare Pages:

1. Connect your GitHub repository to Cloudflare Pages
2. Set build command to: `echo "No build required"`
3. Set build output directory to: `/`
4. Deploy automatically on push to main branch

## File Structure

```
communication-style-assessment/
├── index.html              # Main application file
├── js/
│   └── translations.js     # Internationalization translations
├── README.md              # This file
└── .gitignore            # Git ignore file
```

## Languages Supported

- **English** (en) - Default language
- **Chinese Simplified** (zh) - 中文
- **Portuguese** (pt) - Português
- **Vietnamese** (vi) - Tiếng Việt

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- Local Storage for language preferences

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

Feel free to contribute translations for additional languages or improvements to the assessment.

## License

Based on the Douglas & Douglas (1992) Communication Style Assessment
Copyright © Preferred Training Networks 2025

## Attribution

This assessment is based on the work by Douglas & Douglas (1992) and is used for educational purposes.