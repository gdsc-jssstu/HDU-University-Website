# 🏫 HDU-University-Website 🎓

HDU (Hypothetical Dream University) Website is a beginner-friendly open-source project to challenge the community to create an aesthetically designed and responsive university website for a university called HDU. Essentially we would like to reimagine the [JSSSTU website](https://jssstuniv.in), built by the community. Both beginners in web development and graphic designers are welcome to work together to make HDU's website look amazing. The website must contain all the pages that a general university website may have, you can have a look at [JSSSTU's website](https://jssstuniv.in) for an idea of this.

> - Before contributing look into our [CONTRIBUTING GUIDELINES](./CONTRIBUTING.md)
> - Our Code of Conduct [CODE OF CONDUCT](./CODE_OF_CONDUCT.md)

## Tech Stack Used

The tech stack used here is:

- HTML5

- CSS3

- JavaScript

## Project Structure

The project structure is as follows:

```bash

    - index.html (Home Page)
    - pages (Folder)
        - about.html
        - admission.html
        - departments.html
        - facilities.html
        - research.html
        - contact.html
        - ...
    - public (Assets, CSS, and JS Folder)
        - assets (Folder)
            - images (Folder)
                - favicon.ico
                - logo.png
                - ...
        - css (Folder)
            - index.css
            - about.css
            - admission.css
            - ...
        - js (Folder)
            - index.js
            - about.js
            - admission.js
            - ...
```

- The project structure is subject to change as the project progresses.
- The naming scheme of the HTML, CSS and JavaScript files are to ensure separation of concerns and clarity while development. The HTML files are named after the pages they represent, the CSS files are named after the HTML files they represent, and the JavaScript files are named after the HTML files they represent.
- Feel free to use any non-copywritten images, icons, etc. in the project.

## Project Setup Instructions

- Fork and clone the repository using
  ``` git clone https://github.com/gdsc-jssstu/HDU-University-Website ```
- Open the project in your favourite code editor
- Start working on the project
- [Recommended] Use Live Server to see the changes you make in real-time.

## Final Vision/Guiding Designs of the project

- These are designs to help visualise and guide the development of the project. The final version of the project may or may not look like this. Creative freedom is encouraged.
- Click [here](https://www.figma.com/proto/aILrEaqatJsdRCtWM5KgE6/Jssstu-web?node-id=15-97&starting-point-node-id=15%3A97) for the UI design and prototype of the project.

## Intended Final Project

- A responsive and aesthetically designed university website for a university called HDU, where current and prospective students can get details about the university's facilities, departments, research, admission criteria, admission portal, etc.

## Maintainers

- [Sayed Afnan Khazi](https://github.com/Sayed-Afnan-Khazi)
- [Aryan Thakur](https://github.com/Aryan-Kumar-Thakur)

## Steps to use Docker 

```bash
docker build -t your-image-name:tag .
```

```bash
docker run -itd -p 80:80 -p 443:443 your-image-name:tag
```
