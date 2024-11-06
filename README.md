# Senseable GitHub Workshop
This repository contains a new (fake) website for Senseable Amsterdam Lab. The website is hosted on [GitHub pages](https://pages.github.com/).

You can access the website [here](https://senseable.github.io/senseable.github.io/).

This repository works exactly as every other repository on GitHub, but it has a special feature: it is automatically published as a website.

If you learn how to contribute to this repository, you will be able to contribute to any other repository on GitHub :) 


## How to contribute

1. Fork this repository
2. Clone the repository to your computer
3. Make changes
4. Push your changes to your fork
5. Create a pull request
6. Wait for the pull request to be reviewed and merged
7. Celebrate! 🎉 Your changes will appear live on the website in a few minutes

## What changes can I make?
1. Create a file in the `researchers` folder with your name as the filename and using `.md` as the extension.
2. Add whatever content you want to the file. You can use [Markdown](https://guides.github.com/features/mastering-markdown/) to format the content. You can use [Giacomo's](researchers/giacomo-orsi.md) file as an example.
3. Add a link to your file in the [`index.md`](index.md) file.


### Advanced (only if you have completed the previous steps)
If you want to preview the website locally, you can run a local website server. GitHub pages websites use Jekyll, a static site generator. You can run a local Jekyll server to preview the website.

To run a local Jekyll server:
1. Install Jekyll. You can follow the instructions [here](https://jekyllrb.com/docs/installation/).
2. Navigate to the repository folder in your terminal
3. Run `bundle exec jekyll serve`
4. Open your browser and go to `http://localhost:4000/`

Now:
- You should see the website running locally
- You can stop the server by pressing `Ctrl + C` in your terminal
- You can make changes to the files and see the changes live on the website