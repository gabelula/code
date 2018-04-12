# README

Experimenting with content.

## Requirements

- transclusion on the content side.
- easy to work with content (writes do not need to know anything about
the code)
- deploy when pushing content into master on content (continuous
deployment on content)

## Option 1

Replace the folder 'content' with the repository 'content' that contains
the content for everything.

- site1
  - git submodule to content

### pros

- it may make easier to work with the shortcodes.

### cons

- it may be hard to decide on the code side which content to use (it can
not be automatically but specifically go to a folder in the content
repo.)

## Option 2

Replace the folder 'content' with only the folder that has the content
for the site inside repository.

- site1
  - git submodule to content/site1

### pros

- it will be easier on the code side to just get the content we need

### cons

- the challenge will be how to work with the shortcodes and transclusion
