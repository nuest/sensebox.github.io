# sensebox.github.io

![senseBox Logo](https://raw.githubusercontent.com/sensebox/sensebox.github.io/master/images/sensebox_wort_und_logo.svg "senseBox Logo")

senseBox website

## Editing the website

Most of the articles and press releases are written with [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). HTML can be used if needed, e.g. for linking to external pages or for embedding images.

### Adding press reports

Add the press report as a markdown file in the `_awards` and `_awards_en` folder. Follow the same schema as existing files.

### Adding awards

Add the award as a markdown file in the format `2015-01-01-topic.md` in the `_press` folder. Follow the same schema as existing files.

### Adding team members biographies

Add the biography as a markdown file in the format `name.md` in the `_team` folder. Follow the same schema as existing files.

## Running the page locally with Jekyll

Clone repository, `cd` into it and run:

```bash
jekyll serve
```

In a Vagrant environment, run:

```bash
jekyll serve --host 0.0.0.0 --force_polling
```
