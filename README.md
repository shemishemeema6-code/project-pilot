# project-pilot
Mission-based collaboration platform for university students. Match skills with projects, build a crew, earn XP and ship portfolio-ready case studies. Built with HTML, CSS and JavaScript.
# Project Pilot

**Connect, Collaborate, Conquer.** Project Pilot is a mission-based collaboration platform concept for university students. Students list their skills, find open projects ("missions") that match them, build a crew, and finish missions to earn a portfolio-ready case study.

**project link:** [[shemishemeema6-code.github.io](https://shemishemeema6-code.github.io/project-pilot/)]

# Screenshots
[screenshot 1]<img width="947" height="469" alt="image" src="https://github.com/user-attachments/assets/ece38d0d-8075-4f65-947b-101a51dd1659" />
[screenshot 2]<img width="945" height="473" alt="image" src="https://github.com/user-attachments/assets/543cc966-e674-4d67-b6ec-1de9c2823f5e" />
[screenshot 3]<img width="945" height="468" alt="image" src="https://github.com/user-attachments/assets/20bdf750-f2e4-4493-8ba8-24292439c3a4" />

## Why I built it

Textbooks teach theory, but real experience comes from building things with other people. Students in different disciplines (developers, designers, marketers, writers) rarely get a simple way to find each other. Project Pilot is my answer: a launchpad where skills meet missions.

## Features

**Home**
- Animated constellation background that reacts to the cursor
- Typewriter headline, live counters and an FAQ

**Launchpad**
- Open missions with a skill match score on every card
- Search by name, goal or skill, and sort by best match or newest
- Post your own mission and join other missions

**Crew**
- Browse sample student profiles and search by name, skill or major
- Shared skills are highlighted, and you can add people to your crew

**Dashboard**
- Editable profile with photo upload and a Skill Arsenal
- XP, ranks (Cadet, Navigator, Pilot, Commander) and six achievement badges
- Active missions with milestone checklists and progress bars
- Confetti when you complete a mission, plus a printable case study

**Accounts**
- Sign in or create an account with a university email (`.edu`, `.ac.in`, `.edu.xx` and similar)

**Quality**
- Fully responsive, keyboard-focus styles, and respects "reduce motion" settings
- Share button with Web Share API and LinkedIn sharing

## Tech stack

- HTML5, CSS3 (custom properties, grid, flexbox, glassmorphism) and vanilla JavaScript
- [Lucide](https://lucide.dev) icons and the Sora typeface from Google Fonts
- HTML canvas for the background animation and confetti
- `localStorage` for saving data in the browser

There are no build steps and no dependencies to install. The whole site is one file: `index.html`.

## Run it locally

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

```bash
git clone https://github.com/shemishemeema6-code/project-pilot.git
cd project-pilot
# then open index.html in your browser
```

## Good to know

- This is a front-end project. Accounts, missions and profiles are stored in your own browser, so other visitors cannot see them.
- Sign-in is a demonstration and does not use passwords.
- The crew profiles and starter missions are fictional samples.

## Roadmap

- Real accounts and shared data with Firebase or Supabase
- Team chat inside each mission
- Applications and approvals for joining a mission
- Notifications and a public portfolio page per student

## Author

**Shemeema Parambath**

- LinkedIn: add your profile link here
- GitHub: [@shemishemeema6-code](https://github.com/shemishemeema6-code)

## License

Released under the MIT License. Feel free to learn from it and build on it.
