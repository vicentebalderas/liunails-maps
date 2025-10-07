# LIUNAILS Maps

A interactive map showing LIUNAILS distributors across Mexico. This web application helps customers find authorized distributors in their area with contact information and social media links.

## Features

- 🗺️ Interactive map with distributor locations across Mexico
- 📍 Clickable markers with distributor details
- 📱 Direct WhatsApp, Instagram, and Facebook links
- 📱 Mobile-responsive design
- 🎨 Modern dark theme UI

## Usage

Simply open `index.html` in your web browser to view the interactive map. The map will automatically load with all distributor locations marked.

### Finding a Distributor

1. Open the map in your browser
2. Navigate to your city or state
3. Click on any marker to see distributor details
4. Use the provided links to contact the distributor directly

## Technology Stack

- **Leaflet.js** - Interactive mapping library
- **OpenStreetMap** - Map tiles
- **Vanilla JavaScript** - No frameworks required
- **CSS3** - Modern styling with CSS custom properties

## Distributors

The map currently shows distributors in the following Mexican states:

- Baja California Sur
- Ciudad de México
- Coahuila
- Jalisco
- Michoacán
- Nayarit
- Nuevo León
- Querétaro
- Sinaloa
- Tabasco
- Veracruz

## Contact Information

Each distributor marker includes:
- Business name
- City and state location
- WhatsApp contact link
- Instagram profile link
- Facebook page link (where available)

## Development

This is a static web application that requires no build process or server. Simply serve the files from any web server or open directly in a browser.

### Adding New Distributors

To add new distributors, edit the `distributors` array in `index.html` and add a new object with the following structure:

```javascript
{
  state: "State Name",
  city: "City Name", 
  name: "Business Name",
  coords: [latitude, longitude],
  links: {
    wa: "WhatsApp URL",
    ig: "Instagram URL", 
    fb: "Facebook URL"
  }
}
```

## License

This project is for internal use by LIUNAILS.
