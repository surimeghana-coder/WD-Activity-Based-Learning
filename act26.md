# Dr. RVR NRIIT FEST 2026

A college fest website for **Dr. RVR NRIIT FEST 2026**, built with HTML and CSS. It presents the fest theme, schedule, guests, activities, food and stalls, DJ night, highlights, and contact/interest registration information.

## Features

- **Navigation bar** with links to Home, About, Schedule, Guests, Activity, DJ, and Contact.
- **Hero section** introducing the fest with the tagline “Celebrate • Connect • Create” and an Explore Fest button.
- **About section** with Celebrate, Connect, and Create cards.
- **Event schedule** showing times, events, and locations.
- **Special guests section** with guest images and descriptions.
- **Games and activities** featuring a Gaming Zone, Competitions, Creative Zone, and Fun Games.
- **Food and stalls** section covering the Food Court, Creative Stalls, and Fun Stalls.
- **DJ Night** section with a Join the Celebration button.
- **Fest highlights** for events, live performances, games, food, and DJ Night.
- **Venue and contact section** with a registration-interest form.
- **Visual styling** using a dark theme, golden accents, hover effects, smooth scrolling, and a mobile responsive media query.

## Technologies Used

- HTML5
- CSS3

## Project Structure

Keep the HTML, CSS, and image files together in the project folder, unless you update the paths in the code.

```text
nriit-fest-website/
├── index.html       # HTML page (use your actual HTML filename)
├── act26.css        # Stylesheet
├── act26.md         # Project documentation
├── homebg.jpg       # Hero background image
├── dj.jpeg          # DJ Night background image
├── modi.jpeg        # Guest image
├── satish.jpeg      # Guest image
└── rahman.jpeg      # Guest image
```

## How to Run

1. Save the HTML code in your HTML file.
2. Make sure the stylesheet is named `act26.css`, as referenced in the HTML.
3. Keep the referenced image files in the correct folder:
   - `homebg.jpg`
   - `dj.jpeg`
   - `modi.jpeg`
   - `satish.jpeg`
   - `rahman.jpeg`
4. Open the HTML file in a web browser.

## Notes

- The schedule and guest details are the content entered in the current HTML and should be confirmed before publishing as an official event announcement.
- The contact phone number is a placeholder (`+91 XXXXX XXXXX`).
- The registration form is currently front-end HTML only. No form submission handler or backend is included, so it does not yet store or send registrations.
- The HTML and CSS contain a few class/markup mismatches that may affect styling. For example, the schedule wrapper uses `table="container"` while the CSS targets `.table-container`; the HTML uses `class="guest"` while the CSS targets `.guests`; and the title font-size rule in the CSS appears malformed. Check these if parts of the design do not display as expected.
- The guest cards in the HTML have nested container markup that may need checking to ensure the cards align correctly.

## Possible Improvements

- Add a real event date, confirmed guest details, and working contact information.
- Connect the registration form to a backend or form service.
- Add form validation and a registration confirmation message.
- Improve mobile navigation and accessibility.
- Fix class-name mismatches and validate the HTML structure.
- Add links to event rules, registration details, or an event gallery.

## License

This project is intended for educational and demonstration purposes. Add a license if you plan to distribute or reuse the project publicly.
