Welcome to the PEP workshop on ROOT6
====================================================

This is a community-contributed place where we collect all our documentation. If you want to contribute to this documentation, follow the steps outlined below. 

## How can I contribute to the documentation?

First off you need a [GitHub](https://github.com) account. Fork the
**PEP-root6** repository, then clone it to your
laptop:

```bash
git clone https://...
cd PEP_root6/
git remote add <my_username> https://github.com/<my_username>/PEP_root6
```

Documentation is written in [Markdown](https://daringfireball.net/projects/markdown/syntax). To
preview the documentation pages locally while you are editing them, go in the root directory of the repository and run:

```bash
cd PEP_root6/
make serve
```

The command will not exit and a local website will be visible at the following address:

> http://localhost:4000

The website uses [GitBook](https://www.gitbook.com/). Editing the pages using your favorite text
editor: whenever you save, the page currently opened in your local preview will be refreshed
automatically.

When you are happy with your modifications, commit them, push them to your repository and open a
pull request, for instance:

```bash
git commit -a -m 'I am happy with my doc'
git push <my_username>
```

then navigate to your GitHub repository online to open a pull request.
