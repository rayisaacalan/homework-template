# Homework Format

## Installing

```bash
quarto use template rayisaacalan/homework-template
```

This will install the extension and create an example .qmd file that you can use as a starting place for your assignment.

## Using

Be sure to replace the fields in the header YAML so that your name, email, assignment title and subtitle are correct.

## Format Options

The `before-body.tex` document partial has the following fields:
 - author
 - institute
 - email
 - title
 - subtitle
 - date

The `header.tex` includes the following functionality:
 - `\note{}` writes a red comment in the margin of the page
 - Changes the look of blackboard bold characters to use AMS Symbol Font B (for certain compilers)



