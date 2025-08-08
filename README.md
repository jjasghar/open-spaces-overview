# Open Spaces Overview Presentation

An interactive presentation about Open Spaces facilitation methodology, built with [reveal.js](https://revealjs.com/). This presentation provides a comprehensive overview of Open Spaces principles, techniques, and best practices for conference and event organizers.

## 📖 About Open Spaces

Open Spaces is a meeting methodology that creates space for organic conversation and self-organization. It's particularly effective for conferences, workshops, and community events where participants want to engage in meaningful discussions around topics they're passionate about.

## 🎯 What This Presentation Covers

- **Open Spaces Principles**: The four core principles that guide Open Spaces sessions
- **The Law of Mobility**: Understanding when and how to move between conversations
- **Best Practices**: Guidelines for respectful participation and effective facilitation
- **Participant Types**: Bumblebees, Butterflies, and other participant personas
- **Facilitation Tips**: How to start, manage, and conclude Open Spaces sessions

## 🚀 Quick Start

### View the Presentation

1. **Online**: Open `index.html` in your web browser
2. **Local Server** (recommended): 
   ```bash
   npm install
   npm start
   ```
   Then navigate to `http://localhost:8000`

### Navigation

- **Next/Previous**: Arrow keys or space bar
- **Overview**: Press `ESC`
- **Speaker Notes**: Press `S`
- **Fullscreen**: Press `F`

## 🛠 Development

This presentation is built on reveal.js 5.0.3. To customize or extend:

### Prerequisites

- Node.js 18.0.0 or higher
- npm (comes with Node.js)

### Setup

```bash
# Clone the repository
git clone https://github.com/jjasghar/open-spaces-slides.git
cd open-spaces-slides

# Install dependencies
npm install

# Start development server
npm start
```

### Testing & Building

```bash
# Run linting checks
npm test

# Build presentation assets
npm run build

# Run comprehensive tests (includes QUnit browser tests)
npm run test:full
```

### Customization

- **Content**: Edit `index.html` to modify slides
- **Styling**: Modify CSS in the `css/` directory
- **Theme**: Change the theme in `index.html` (line 11)
- **Plugins**: Add/remove plugins in the JavaScript section

### Available Themes

The presentation supports multiple themes:
- `white` (current)
- `black`
- `league`
- `beige`
- `sky`
- `night`
- `serif`
- `simple`
- `solarized`

## 📁 Project Structure

```
open-spaces-slides/
├── index.html              # Main presentation file
├── demo.html              # Original reveal.js demo
├── css/                   # Stylesheets and themes
├── js/                    # reveal.js core JavaScript
├── plugin/                # reveal.js plugins
├── examples/              # Additional examples
├── package.json           # Project dependencies
└── README.md             # This file
```

## 🎨 Features

- **Auto-advance**: Slides advance automatically every 15 seconds
- **Slide Numbers**: Displays current slide position
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Markdown Support**: Some slides use Markdown for easier editing
- **Speaker Notes**: Hidden notes for presenters
- **Syntax Highlighting**: Code blocks with syntax highlighting

## 📝 Using in Your Event

This presentation is designed to be used at the beginning of conferences or workshops to introduce participants to Open Spaces methodology. Feel free to:

- Customize the content for your specific event
- Add your organization's branding
- Modify timing and transitions
- Add additional slides with event-specific information

## 🤝 Contributing

Contributions are welcome! Please feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Attribution

- Built with [reveal.js](https://revealjs.com/) by Hakim El Hattab
- Open Spaces methodology developed by Harrison Owen
- Presentation content compiled by [jjasghar](https://github.com/jjasghar)

## 🔗 Resources

- [Official Open Spaces Website](http://www.openspaceworld.org/)
- [reveal.js Documentation](https://revealjs.com/)
- [Open Spaces User's Guide](http://www.openspaceworld.org/users_guide.htm)

## 📧 Support

If you have questions about Open Spaces methodology or this presentation, please:

- Open an issue on GitHub
- Reach out to the maintainer: [@jjasghar](https://github.com/jjasghar)

---

*Made with ❤️ for the Open Spaces community*