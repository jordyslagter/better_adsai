# Better ADSAI

This is a template that improves upon the Zuyd University ADSAI template by
moving its styling from `main.tex` to its own document class `adsai.cls`,
it also merges English and Dutch by way of a document class option.

## Getting started

To get started simply download this repository as a .ZIP, clone it, use it as a
template or fork it.

### Using Dutch/English

By default, the template uses English, however you can switch to Dutch simply
by adding the `dutch` option to the `main.tex` `\documentclass`
definition. For example:

```tex
% default
\documentclass{adsai}
```

```tex
% in Dutch
\documentclass[dutch]{adsai}
```

### Using a different bibliography style

By default, the template uses IEEE-style bibliography, if you want to use APA7,
MLA or something else, simply add it to the `\documentclass` options. For
example:

```tex
% default
\documentclass{adsai}
```

```tex
% using APA7
\documentclass[bibstyle=apa]{adsai}
```

```tex
% both APA7 and Dutch
\documentclass[bibstyle=apa, dutch]{adsai}
```
