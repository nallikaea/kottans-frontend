# Front-End Course

## Navigation

#### General
 0. [x] [Git Basics](#git-basics)
 1. [x] [Linux CLI, and HTTP](#linux-cli-and-http)
 2. [x] [GitHub and Collaboration](#git-collaboration)

#### Front-End Basics
 3. [x] [Intro to HTML & CSS](#intro-to-html--css)
 4. [x] [Responsive Web Design](#responsive-web-design)
 5. [x] [HTML & CSS Practice](#hooli-style-popup)
 6. [ ] JavaScript Basics
 7. [ ] Document Object Model - practice

#### Advanced Topics
 8. [ ] Building a Tiny JS World (pre-OOP) - practice
 9. [ ] Object oriented JS - practice
10. [ ] OOP exercise - practice
11. [ ] Offline Web Applications
12. [ ] Memory pair game — real project!
13. [ ] Website Performance Optimization
14. [ ] Friends App - real project!

## Git Basics
:smile:
- Сourse **Version Control with Git** - FINISHED.:star:
 This is a very good course for beginners. The material is presented in an accessible and high quality. He helped me quickly understand the version-control system GIT and use the basic commands such as for example:

  - git init and git clone - for start the project;
  - git log and git status;
  - git add and git commit - to make commits;
  - git diff - to see detailed differens;
  - .gitignore - for ignore files by GIT;
  - git branch, git checkout and git merge - for working with branches;
  - git revert, git reset - for edit/delete commits;
  - etc.

- **Introduction Sequence, Push & Pull** (learngitbranching.js.org) - COMPLITED.:star:
 This resource gave me additional knowledge about working with branches and also taught me how to work with remote repositories. Commands, I learned here:
  - git rebase - type of merging;
  - git fetch - download;
  - git pull - git fetch + git merge;
  - git push - share my work;
  - and other;

- Repository "kottans-frontend" and README.md file with my impressions about learned materials created.:feet:

- Pull-request to Kottans/mock-repo with my greeting and cat sended.:love_letter:

## Linux CLI, and HTTP
:smile:
- Сourse **Linux Survival (4 modules)** - FINISHED.:star:
 This course taught me how to use CLI. I had an experience with command line it the past, but repetition was very useful for me. I want to write some commands here:
  - ls - list of content in directory;
  - more - properties;
  - mkdir <name> - make directory;
  - mv <from> <to> - move, rename;
  - cd <where> (cd ..) - chenge directory (up one directory);
  - pwd - print working directory;
  - cp <name> <name> - copy;
  - rm <name>, rmdir <name> - remove file and directoty. To remove directory tree -r need to be added;
  - security atributes: r(read), w(write), x(execute); Users can be owner, group or other;
  - chmod (example: chmod ugo-rwx) - change security mode;
  - man is for manual;
  - find ~ -name "name*"
  - cat file1 file2 > file;
  - lpr, lpq, lprm -commands for printer;
  - df - free disk space;
  - ps aux - show active procesess;
  - grep <text> - find some text in file;
  - kill, kill -9 <idp> - kill some process by ID;

 [This](https://github.com/nallikaea/kottans-frontend/blob/main/task_linux_cli) is folder with screenshots I made during course pass. :blush:

 ![Screencli](https://github.com/nallikaea/kottans-frontend/blob/main/task_linux_cli/conclusionscli.png)

 - Article **HTTP: The Protocol Every Web Developer Must Know** - READED.:star:

  This is very fullness article about how HTTP works. It tells about URL, status codes and request/response headers, connection handling, identification, authentication and caching. I learned something about it during my study at the university, and this article helped me to remember and learn many new information, for example about security.

  Hypertext Transfer Protocol is the stateless, application-layer protocol for communicating between distributed systems, and is the foundation of the modern web. :muscle::muscle::muscle:

   ![URL](https://github.com/nallikaea/kottans-frontend/blob/main/task_linux_cli/http1-url-structure.png)

 Request verbs, which is I definitely will use:
  - GET: fetch an existing resource.
  - POST: create a new resource.
  - PUT: update an existing resource.
  - DELETE: delete an existing resource.
  - OPTIONS: used to retrieve the server capabilities.

## Git Collaboration

- Сourse **GitHub & Collaboration** - FINISHED.:star:
 On this course I learned how to work on the projects witch contains in remote repositorie on the example of a GitHub and repeat comands, which I learned on **Introduction Sequence, Push & Pull** (learngitbranching.js.org). Also I leadned how to fork, how to review existing work, how to use filters of commits and much more other things.

 The thing I want to note here how to create pull-request:
  - clone your fork down to your machine;
  - make some commits;
  - push the commits back to fork;
  - create a new pull request and choose the branch that has your new commits.

 ![GfTC](https://github.com/nallikaea/kottans-frontend/blob/main/task_git_collaboration/image_2020-10-23_16-11-58.png)

- **Ramping Up, Moving Work Around, To Origin and Beyond** (learngitbranching.js.org) - COMPLITED.:star:

 ![lb1](https://github.com/nallikaea/kottans-frontend/blob/main/task_git_collaboration/image_2020-10-23_17-38-10.png)
 ![lb2](https://github.com/nallikaea/kottans-frontend/blob/main/task_git_collaboration/image_2020-10-23_17-55-24.png)

## Intro to HTML & CSS

  :smile:
  - Сourse **Intro to HTML & CSS (Eng)** - FINISHED.:star:

  This was simple intro course for beginners with good visualizations about main concepts of HTML and CSS. Here I learned about basic HTML-tags (< body >, < div >, < p >..) and basic CSS how to change font, color, text style, etc.

  ![html](https://github.com/nallikaea/kottans-frontend/blob/main/task_html_css_intro/2020-10-28.png)

  - Сourse **Learn HTML(Eng)** (Codeacademy) - FINISHED.:star:
 
  This is a more compleх HTML-course that covers many rules for writing code elements. By taking this course, you can write a good informational website.
  
   ![semhtml](https://github.com/nallikaea/kottans-frontend/blob/main/screens/img_sem_elements.gif)
   
  Here I find out how to make tables and forms, and learn about Semantic HTML witch clearly defines its content: < form >, < table >, and < article >... 
  
  ![html2](https://github.com/nallikaea/kottans-frontend/blob/main/task_html_css_intro/2020-10-28%20(2).png)
  
  - Сourse **Learn CSS(Eng)** (Codeacademy) - FINISHED.:star:

  This Cascading Style Sheet course is very good and long. He tells not only how to add colors and fonts to your HTML-code, but also how to build a real functional layout and how to add interactive elements to website using only CSS, without any Javascript code. Amazing.

  ![css](https://github.com/nallikaea/kottans-frontend/blob/main/task_html_css_intro/2020-10-28%20(1).png)

  These three courses provide a good foundation to write your first high-level interactive website. I will definitely use it all.
  
## Responsive Web Design
  
  😛
 
  - Сourse **Responsive Web Design Fundamentals** - FINISHED.:star:
  
  The main concepts of responsive web design I learned here:
   - web-site autoscale to screensize < meta name="viewport" content="width=device-width, initial-scale=1.0" >;
   - start design your site from the smallest viewport;
   - prefer relative units for widths for elements;
   - breakpoints;
   - flexbox and grid layouts;
   - tap-targets size to 48x48 px minimum;
   
  Patterns for responsive design:
   - Column Drop;
   - Mostly Fluid;
   - Layout Shifter;
   - Off Canvas.
   
  ![rwd](https://github.com/nallikaea/kottans-frontend/blob/main/task_responsive_web_design/2020-10-30%20(1).png)
  
  - **Flexbox Froggy Game**  - FINISHED.:star:
 
  _The main comands of flexbox design:_
   - justify-content - aligns elements horizontally:
     - flex-start: on the left side of the container.
     - flex-end: on the right side.
     - center: centered.
     - space-between: items are displayed with equal spacing between them.
     - space-around: items are displayed with equal padding around them. 
   - align-items (align-self) - aligns items vertically:
     - flex-start: items are aligned to the top of the container.
     - flex-end: bottom-aligned.
     - center: vertically centered.
     - baseline: drawn at the baseline of the container.
     - stretch: stretch to fill the container.
   - flex-direction - the direction in which the elements will be positioned in the container:
     - row: elements are laid out in the direction of the text.
     - row-reverse: displayed in reverse order to the direction of the text.
     - column: from top to bottom.
     - column-reverse: from bottom to top.
   - order can be positive or negative; default 0;
   - flex-wrap:
     - nowrap: elements are automatically sized to fit in one row.
     - wrap: items are automatically wrapped to a new line.
     - wrap-reverse: items automatically wrapped to a new line, but the lines are in reverse order.
   - flex-direction + flex-wrap = flex-flow.
   - align-content specifies how multiple rows should be separated from each other:
     - flex-start: rows are grouped at the top of the container.
     - flex-end: at the bottom.
     - center: vertically centered.
     - space-between: rows are displayed with equal distances between them.
     - space-around: with equal spacing around them.
     - stretch: rows are stretched to fill the container evenly.
    
   ![frog](https://github.com/nallikaea/kottans-frontend/blob/main/task_responsive_web_design/2020-10-30.png)
   
   ## Hooli-style Popup
   
   This is my soluchion of this task. Hopy U like 😊

  [Demo](https://nallikaea.github.io/html-css-popup/) 
  
  [Code base](https://github.com/nallikaea/html-css-popup)


