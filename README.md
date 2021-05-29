https://psirusteam.github.io/MuestreoEducacionales/

Esta es la página del manual de __Muestreo en estudios educacionales__

If you mean you would like to use GitHub pages to publish or deploy your bookdown project and:

a) you would like to place the rendered book (i.e., the folder _book is not in your .gitignore file) on GitHub
b) further, you are OK with placing your rendered book in a folder on your "master" GitHub branch
c) even further, you are OK with using a project domain name like http(s)://<username>.github.io/<projectname>

Then you can take advantage of a neat trick with GitHub pages which allows you publish to GH pages from the master branch /docs folder. To do that:

1. Configure source for GH pages through GitHub website as master branch /docs folder
2. Go to your _bookdown.yml file and add output_dir: "docs" on a line by itself
3. Serve/preview your book locally
4. Push to GitHub, you should see it there.
  
  https://github.blog/2016-08-17-simpler-github-pages-publishing/
