# Formatting and Hosting Using a Software Stack

### Purpose

This Readme will cover how to host and format a resume using Markdown, a Markdown editor, GitHub pages and Jekyll.

It will also use Andrew Etter's book  *Modern Technical Writing: An Introduction to Software Documentation* to teach their key principles.

### Prerequisites

* A Markdown editor (I use Atom. See in the More Resources section)

* A resume to be formatted into Markdown

* A GitHub account

### Instructions

#### Why Use Markdown?

Andrew Etter in his book *Modern Technical Writing: An Introduction to Software Documentation*(2016) states that, "It's the most widely used lightweight markup language in the
world and has the cleanest syntax". This means that it is easy for a beginner to use and get a acceptable end result, as it is common there are many applications that help you to write it. This is important as many times when a group needs documentation, it is helpful to get several people to contribute. Markdown as well as other lightweight markup languages produce the same result throughout editors. This is why lightweight markup languages and specifically Markdown is helpful for your resume. You can easily write it and edit it, as well as have people edit it for errors and give you back the edit in the same format.

#### Prerequisites

1. Download a Markdown editor

  * Consider using and editor that allows for a Markdown preview. I use [Atom](https://atom.io/)

2. Convert your resume into the Markdown format

  * Follow a tutorial such as [this one](https://helloacm.com/markdown-markup-language-quick-tutorial/) if you need guidance

3. Sign into your GitHub account on the [GitHub website](https://github.com/)

  * If you do not have an account, sign up for one

### Why use GitHub?

GitHub can be used as Distributed Version Control(DVCS). Andrew Etter states, "DVCS have better
performance, allow for offline work, and are superior for concurrent work
on the same file."(2016) This helps keep everything you need for your resume in one place. You will see later in the instructions you will need to create multiple files for your resume and GitHub will keep it organized.

#### Adding Your Resume to GitHub

1. Create a new repository in your GitHub account

  * Name it *your-GitHub-username*.github.io

  * Make the repository public (this allows someone to access your resume)

  * You should now be on your repository page in GitHub.

2. Click *Add file* near the top right of GitHub
![Add file location](https://i.imgur.com/i3TAvRL.png)
3. Click Upload files
4. Drag your resume.md file into the window

  * Make sure Commit directly to the main branch is selected

  * Press the Commit changes button

5. Click on your newly added file
6. Click the Pencil icon to edit the file
![Pencil icon location](https://i.imgur.com/4mwj3xG.png)
7. Change the files name to index.md
8. Commit the change as done before

### Why use GitHub pages?

Andrew Etter explains, "Even the best documentation, like software,
eventually goes out of date.", "Hosting your content on a website gives you
the power to fix inaccuracies almost instantly."(2016) This is great for a resume as it allows someone to always check the same place for the most up to date version. GitHub pages is designed to work with Markdown and Jekyll. Jekyll allows for some additional formatting and theming. I will be showcasing some Jekyll in this section of the instructions.

#### Setting Up GitHub pages

1. Click on Settings near the Add file button
![Setting location](https://i.imgur.com/B7HJY2M.png)
2. Click on the Pages tab located in the left side bar under Code and automation
3. Set the source button to build the site from the main branch in the root folder
![Source reference](https://i.imgur.com/e5vqzbb.png)
4. Navigate back to the main page of your repository using the Code tab in the top bar where the Settings tab is
5. Click on the *Add file* button
6. Click *Create new file*
7. Name the file README.md

  * This file is for any information you would like to give to the viewer

8. Create another new file

  * Name this one _config.yml

  * This file is for Jekyll formatting

#### Formatting with Jekyll

1. Go back to the Pages tab in Settings
2. Click *Change Theme* under the Theme Chooser section
![Change theme location](https://i.imgur.com/gl65J7L.png)
3. Choose a theme

  * Once you find a theme you like click the green *Select theme* button

4. Navigate to your _config.yml files
5. Click on the pencil icon
6. Write title: *your desire title here*
7. You should have a complete GitHub Pages resume if you go to the link *your-GitHub-username*.github.io
![Resume being shown in a gif](https://i.imgur.com/Pu16TmU.gif)

### More Resources

* [A Markdown tutorial](https://helloacm.com/markdown-markup-language-quick-tutorial/)

* Andrew Etter's book [Modern Technical Writing: An Introduction to Software Documentation](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

* [Atom download](https://atom.io/)

* [How to set up and use Atom](https://www.portent.com/blog/content/atom-markdown.htm)

### Authors and Acknowledgements

* Seth Peters

* My group members Carl Wiebe, Sangmin Lee, and Steven Zhang

* Andrew Etter for his book [Modern Technical Writing: An Introduction to Software Documentation](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

### FAQ
* Why is Markdown better than a word processor?

  Markdown is an easy to learn text language that is easily converted into HTML. If the text will be published online, Markdown makes this process easier than the other common word processors.

* Why don't my bullet  lists show up correctly?

  After you place the * make sure to add a space before writing the content of your list entry.
