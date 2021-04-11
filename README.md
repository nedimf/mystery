# Mystery

## Introduction

Mystery is a tool to generate mystery ingredients for your next project. It was
inspired by the Food Network show Chopped, since in the show, contestants have
to prepare a dish that incorporates a basket of mystery ingredients.

## Usage

Using Mystery is simple. Just run the `mystery` program in your terminal.
Here's an example:

```
$ mystery generate

Voila! Your mystery ingredients have been generated! You'll be making a project
in the Go language with the following ingredients:

- Mind Blown (https://github.com/mind/blown): A package that randomly inserts
the 🤯 emoji into your project's output.
- Another One (https://github.com/another/one): A package that simply prints
out the phrase 'another one' like DJ Khaled.
- Cool Project (https://github.com/cool/project): A package to make cool things
happen!

Use this snippet if you want to import it:

import (
        "github.com/mind/blown"
        "github.com/another/one"
        "github.com/cool/project"
)

Good luck on your mystery project!
```

After you get your ingredients, the rest of the creativity is all up to you. We
recommend that you try to read into each of the tools, and brainstorm what kind
of project, big or small, you can make with it.

## Languages

The project currently supports the following languages:

- Go (https://golang.org)
- Swift (https://swift.org)

With more coming soon!

## Download

You can download the latest version of the `mystery` CLI tool in the releases
section. The tool is built for most common operating systems and CPU 
architectures. Don't see yours? Create an issue and we can add it!

## Contribute

The main contributions needed are to the ingredients dataset. We want to
provide an ever growing list of quality, locally sourced ingredients. If you
feel like you have a good ingredient to add, please create a pull request and
add it.

If you want to add a new language support, we are also accepting pull requests
for that. You can compare to the existing languages that are supported to see
what contributions are needed to support a language.

## Issues

The tool is currently `v0` and can be used reliably, however, until it is `v1`,
the commands, flags, arguments and behavior are subject to change. As such,
please provide any bugs or behavior feedback as issues in the project so that
it can be useful for everyone!

## Futures

As the project evolves, here's some future features that might come about. If
you have a feature, please create an issue for it:

- Ability to save ingredients for future reference
- Ability to generate a skeleton package
- Ability to generate a boilerplate project
- Something cooler? Shoot it our way!

Eventually, I would like to make mystery not just a CLI, but a monthly “mystery
challenge” generator. I’d like to make a website and a Twitter where the 
community can all try to make their best project out of the same mystery 
ingredients (kind of like the show Chopped!) Stay tuned for this!