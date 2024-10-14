
# Lab 05 - Markdown

## Timeline
| Event     | Date                  |
|-----------|-----------------------|
| Assigned  | Monday, September 30, 2024 |
| Deadline  | Friday, October 11, 2024 |

![Lab 5 Assignment](https://github.com/allegheny-college-cmpsc-104-Fall-2024/lab05_solution/blob/main/graphics/markdown.png)

## Project Goals
-  Gain a comprehensive understanding of Markdown syntax and its application in creating web content. Students will demonstrate proficiency in formatting text, inserting images, and linking to external resources.
- Learn the fundamentals of web development through Jekyll, an open-source static site generator.
- Demonstrate the ability to deploy a live website using GitHub Pages, making the personal portfolio accessible on the internet.

## Tools
- A computer
- Git & GitHub account
- Ruby and Jekyll

## Learning Outcomes
These assignment learning outcomes contribute to the following course learning outcomes described in the course syllabus:

1. Describe and explain processes such as software installation or design for a variety of technical and non-technical audiences ranging from inexperienced to expert.
2. Use professional-grade integrated development environments (IDEs), command-line tools, and version control systems to compose, edit, and deploy well-structured, web-ready documents and industry-standard documentation tools.
4. Identify and apply appropriate conventions of a variety of technical communities, tools, and computer languages to produce industry-consistent diagrams, summaries, and descriptions of technical topics or processes.

## Introduction
This lab assignment focuses on creating a personal portfolio using Jekyll, a popular static site generator, and Markdown, a lightweight markup language.

### Objective
Develop a personal portfolio website that effectively showcases your skills, projects, and experiences etc. This site will be created using Jekyll and customized with Markdown, demonstrating your ability to produce web-friendly content.

### Importance of the Assignment
This project allows you to apply practical web development skills while creating a platform for personal branding and professional showcasing.

### What You Will Learn
- **Markdown Mastery**: Gain proficiency in using Markdown for web content creation.
- **Web Development with Jekyll**: Learn to set up and customize a Jekyll site, understanding site configuration and theme customization.
- **Version Control and Publishing**: Utilize Git for version control and GitHub Pages for online publishing.

## Instructions
- Use the provided example in the `jekyll-portfolio` repository as a starting point.
- Customize your site by **adding at least three Markdown pages** that detail your professional background, projects, and contact information.
- Ensure your site is visually appealing and navigable.
- Create a new branch named `gh-pages` in your repository.
- Deploy your site through **GitHub Pages**.
    1. Switch to the `gh-pages` branch: git checkout -b gh-pages.
    2. Push the `gh-pages` branch to GitHub: git push -u origin gh-pages.
    3. Navigate to the repository’s Settings > Pages.
    4. Set the source for GitHub Pages to the gh-pages branch.
    5. Verify that your site is live.

### _Notes_: 
- Ensure that all links are functional and that the site is optimized for readability and accessibility.
- The site must be deployed on GitHub Pages to be considered complete.

## Resources
- [Jekyll’s official documentation](https://jekyllrb.com/docs/)
- [Markdown Guide](https://www.markdownguide.org)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

## Deliverables
Submit the URL of your GitHub Pages site below.

**/Katies-site**

## Project Assessment
- **Content Organization (10%)**: Content should be well-organized, with logical structuring that makes navigation intuitive.
- **Creativity and Personalization (20%)**: The portfolio should reflect a personal touch and creative approach to content presentation.
- **Functionality and Usability (10%)**: All website features must function correctly, including links, navigation, and media content.
- **Technical Implementation (30%)**: Effective use of Jekyll and Markdown (at least three Markdown pages), demonstrating understanding of static site generation and content formatting.
- **GitHub Pages Deployment (20%)**: Successful deployment of the site on GitHub Pages, with the site being publicly accessible and performing smoothly.
- **GatorGrader Compliance (10%)**: Meets all GatorGrader criteria.

## Gator Grade
### GatorGrade Checks for Immediate Feedback

To provide immediate feedback on your submissions, we're utilizing GatorGrade. Upon submission, if there's a thick red X, it indicates missing components. This X will turn into a green check mark once your submission is complete. For details on what's missing, click on the red X.

To meet the lab assignment's baseline writing and commit requirements, you can use the department's `GatorGrade` tool. Ensure Python3 is installed on your computer (check with `python --version`). If Python is not installed, please follow these guides:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [Setting Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Installing `GatorGrade`:

- [Install](https://pipx.pypa.io/stable/) [pipx](https://pipx.pypa.io/stable/) if you haven't already (`pip install pipx`).
- Install `GatorGrade` using pipx (`pipx install gatorgrade`).
- Running `GatorGrade`:
 `gatorgrade --config config/gatorgrade.yml`

Good luck!
