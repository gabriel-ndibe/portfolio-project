
# Portfolio Project

## Overview
This is a multi-page web application built with HTML, CSS, and JavaScript, showcasing a personal portfolio for a UNILAG statistics undergraduate. It features:
- **Home Page** (`index.html`): A responsive profile card with an avatar, name, role, email, bio, hobbies, dislikes, and social links, styled with a vibrant gradient and teal accents.
- **About Me Page** (`about.html`): Five sections (Bio, Goals, Areas of Low Confidence, Note to Future Self, Extra Thoughts) with alternating backgrounds for visual appeal.
- **Contact Us Page** (`contact.html`): A form with client-side validation (Name, Email, Subject, Message) using `aria-describedby` for accessibility. The Message field requires at least 10 characters.

The design is inspired by clean, Netflix-like aesthetics, with responsive layouts for mobile (414px) and desktop (1440px) screens. Features include:
- Navigation with `target="_blank"` and `rel="noopener noreferrer"`.
- Current time displayed via `Date.now()` on the Home page.
- Accessibility with `aria-label` on the name and form error messages.
- Testing attributes with `data-testid` (e.g., `page-header`, `profile-card`).

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/gabriel-ndibe/portfolio-project.git
