💌 Sorry Wrapped

A small interactive apology webpage designed as a digital love letter

Sorry, Wrapped turns a simple apology into an interactive, scroll-based experience with an envelope reveal, memories, animated numbers, promises and a final conversation !!

## Live Page

## View the live page
https://storymintstudio.github.io/sorry-special-webpage/

## About

The page is designed to feel like a personal, handmade apology rather than a conventional website.

It combines:

Editorial typography

Warm paper-inspired colors

Interactive gestures

Scroll-snap storytelling

Subtle animations

Responsive design

Light and dark themes

Personal memories and promises

## Sections
1. Cover — The Envelope

The experience starts with a digital envelope.

Drag the ribbon sideways to unwrap it and reveal the apology.

Interaction:

Drag the ribbon

Reveal the message

Click "Open it with me" to continue

2. What I Actually Did

A straightforward explanation of what went wrong.

The section intentionally avoids excuses and focuses on acknowledging the mistake.

3. The Little Things I Miss

An interactive collection of small memories.

Each card can be tapped to reveal a personal note:

Tiny café moments

Rainy nights

2 a.m. conversations

Your song

Your side of the couch

Sunday mornings

4. The Numbers Only We Know

A playful statistics section containing relationship-specific numbers.

The statistics are hidden behind a draggable pull tab and animate into view when revealed.

5. What I'm Actually Promising

A handwritten-note-inspired section containing specific promises instead of a generic "I'll do better."

6. Last Page

The final section asks whether the two people can talk properly in person.

It provides two responses:

Yes, I loved this

Not yet, but thank you

🎨 Design

The visual style uses a warm, nostalgic paper aesthetic.

Color palette
Color	Purpose
#FBF2E4	Cream background
#FFFCF6	Paper/card background
#221A14	Primary text
#D2604E	Main red
#B2493A	Deep red
#F3C0C8	Pink accent
#D9A930	Gold accent
#C68B61	Brown accent

The website also includes a dark theme that automatically follows the user's system preference.

## Typography

The project uses three Google Fonts:

Fraunces — headings and handwritten/editorial feeling

Inter — body text and interface elements

Space Mono — labels, tags, statistics, and technical details

## Technologies

Built using plain web technologies:

HTML5

CSS3

JavaScript

SVG icons

Google Fonts

Intersection Observer API

Pointer Events API

CSS Scroll Snap

No frameworks or build tools are required.

## Project Structure
sorry-wrapped/
├── index.html
├── style.css
└── README.md

## Running Locally

Clone or download the project and open index.html in a browser.

Or run it with a simple local server:

python -m http.server 8000


Then open:

http://localhost:8000

## Responsive Design

The layout adapts to different screen sizes.

On smaller screens:

Cards switch to a two-column layout

Section spacing is reduced

Typography scales using clamp()

Interactive elements remain touch-friendly

On larger screens:

Editorial page numbers appear on the right

Content receives additional horizontal breathing room




## Customization

Most of the personal content can be changed directly inside index.html.

Look for:

<h1>I got it <em>wrong!</em></h1>


and the sections containing:

What I actually did

The little things I miss

The numbers only we know

What I'm actually promising


You can replace these messages, memories, statistics and promises with your own.



📄 License

This project is free to use and customize for personal projects

If you're sharing or publishing a modified version, consider crediting the original project
## Drafted with AI and customized by Storymint Studio
