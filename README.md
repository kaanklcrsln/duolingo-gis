[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/BhShQpq1)

# DuoGIS - Geography Game

A React-based geography learning game built with OpenLayers for interactive map visualization.

<img width="1920" height="1080" alt="BeaComputerDuo_00000" src="https://github.com/user-attachments/assets/3bca5ec1-caab-4411-95bd-bbd9c14b7738" />

## Features

- 🗺️ Interactive world map with OpenLayers
- 🌍 Country highlighting on hover
- 🌙 Dark mode toggle
- 📊 Statistics display (streak, gems, health)
- 📱 Responsive design
- 🎮 Game-like interface inspired by Duolingo

## Technologies Used

- **React** - Frontend framework
- **Vite** - Build tool and development server
- **OpenLayers** - Interactive maps
- **GeoJSON** - Geographic data format
- **CSS3** - Styling with dark mode support

## Installation

1. Clone the repository:
```bash
git clone https://github.com/GMT-458-Web-GIS/geogame-kaanklcrsln.git
cd geogame-kaanklcrsln
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:3000`

## Project Structure

```
src/
├── components/
│   ├── Navbar.jsx      # Bottom navigation bar
│   └── Navbar.css      # Navigation styles
├── pages/
│   ├── Main.jsx        # Main game page with map
│   ├── Main.css        # Main page styles
│   ├── Intro.jsx       # Introduction page
│   └── Intro.css       # Intro page styles
├── App.jsx             # Main app component
├── App.css             # Global app styles
└── main.jsx            # Entry point
```

## Features in Detail

### Interactive Map
- Built with OpenLayers for smooth map interactions
- Country boundaries with hover highlighting
- Custom styling with green highlight color (#89e219)

### User Interface
- Clean, modern design inspired by Duolingo
- Dark mode with smooth transitions
- Bottom navigation with SVG icons
- Top statistics bar showing streak, gems, and health

### Responsive Design
- Mobile-friendly layout
- Adaptive components for different screen sizes

## Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

### Map Integration

The map uses GeoJSON data for country boundaries and implements hover effects using OpenLayers vector layers. Countries are highlighted when the mouse hovers over them.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is part of the GMT 458 Web GIS course.

## Author

Created by [kaanklcrsln](https://github.com/kaanklcrsln) for GMT-458 Web GIS course.
