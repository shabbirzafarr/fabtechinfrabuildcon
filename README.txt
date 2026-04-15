======================================================
  FABTECH INFRA BUILDCON — WEBSITE PACKAGE
  Proprietor: Tanveer Akhter
======================================================

HOW TO USE THIS WEBSITE
------------------------
1. Open index.html in any browser to preview the site.
2. To go live, upload the entire "fabtech" folder to your web hosting.

HOW TO ADD YOUR PHOTOS
------------------------
Simply drop your image files into the correct folders below.
The website will automatically display them — no code editing needed!

FOLDER STRUCTURE:
-----------------

fabtech/
│
├── index.html              ← Main website file (open this in browser)
│
└── images/
    │
    ├── hero/
    │   └── family-cover.jpg     ← YOUR FAMILY PHOTO (cover banner)
    │                               Recommended size: 1920 x 600 px
    │
    ├── politicians/
    │   ├── politician-1.jpg     ← Meeting with Leader / MLA #1
    │   ├── politician-2.jpg     ← Meeting with Leader / MLA #2
    │   ├── politician-3.jpg     ← Meeting with Leader / MLA #3
    │   ├── politician-4.jpg     ← Meeting with Leader / MLA #4
    │   └── politician-5.jpg     ← Meeting with Leader / MLA #5
    │                               Recommended size: 1200 x 600 px
    │
    ├── work/
    │   ├── work-1.jpg           ← Project / Site Work Photo #1
    │   ├── work-2.jpg           ← Project / Site Work Photo #2
    │   ├── work-3.jpg           ← Project / Site Work Photo #3
    │   ├── work-4.jpg           ← Project / Site Work Photo #4
    │   ├── work-5.jpg           ← Project / Site Work Photo #5
    │   └── work-6.jpg           ← Project / Site Work Photo #6
    │                               Recommended size: 1200 x 700 px
    │
    └── contact/
        └── tanveer-profile.jpg  ← YOUR PERSONAL PHOTO (Contact page)
                                    Recommended size: 400 x 500 px

IMPORTANT NOTES:
----------------
- Image files MUST be named exactly as shown above (e.g. politician-1.jpg)
- Supported formats: .jpg, .jpeg, .png, .webp
- After adding images, refresh the browser to see them

AFTER ADDING IMAGES — CODE CHANGES REQUIRED:
---------------------------------------------
For each image you add, find the matching comment in index.html and
replace the placeholder <div> with the <img> tag shown in the comment.

Example — Family cover photo:
  FIND:    <!-- To show your family photo, replace the div below with: -->
  REPLACE: <img class="cover-img-el" src="images/hero/family-cover.jpg" alt="Akhter Family"/>

Example — Leader photo slot 1:
  FIND:    <!-- SLOT 1: Replace div with -->
  REPLACE: <img class="slide-img-el" src="images/politicians/politician-1.jpg" alt="Meeting 1"/>

CONTACT DETAILS TO UPDATE IN index.html:
------------------------------------------
Search for these and replace with your real details:
- tanveerakhter@fabtechinfra.com  → your real email
- +91 XXXXX XXXXX                 → your real phone number
- Maharashtra, India              → your full address

======================================================
  Website built for Fabtech Infra Buildcon © 2025
======================================================
