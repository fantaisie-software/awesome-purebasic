# Contributing

Guidelines to submitting contributions to the [Awesome PureBasic] project.


-----

**Table of Contents**

<!-- MarkdownTOC autolink="true" bracket="round" autoanchor="false" lowercase="only_ascii" uri_encoding="true" levels="1,2,3" -->

- [Introduction](#introduction)
- [Submitting New Resources Links](#submitting-new-resources-links)
    - [Don't Use Issue to Submit Links](#dont-use-issue-to-submit-links)
- [Eligible Resources Types](#eligible-resources-types)
    - [Source Code](#source-code)
    - [Tutorials](#tutorials)
    - [Books and Courses](#books-and-courses)
    - [Libraries and Tools](#libraries-and-tools)
- [FAQ](#faq)
    - [Why Version-Control?](#why-version-control)
    - [On Publicly Available Code Without License](#on-publicly-available-code-without-license)

<!-- /MarkdownTOC -->

-----

# Introduction

The purpose of the Awesome PureBasic project is to provide a community-managed curated list of links to PureBasic-related resources.

The definition of "PureBasic-related resources" also encompasses resources from other languages (like FAsm, YAsm, [SpiderBasic] and even C) when these are of direct interest to PureBasic usage — for example, in interfacing PureBasic with C libraries, etc.

[SpiderBasic] specific resources are beyond the scope of this project, unless they directly relate to PureBasic.

# Submitting New Resources Links

New links to resources must be contributed via pull requests, by editing the `README.md` file on a forked repository and submitting a pull request.

Links to illegitimate/unauthorized resources _will not_ be included in this project. Any source code and resource that does not bare an _explicit_ license or permission of reusability is to be considered as copyrighted material. 

## Don't Use Issue to Submit Links

Please, don't open an issue to submit a resource link, hoping that other will add it for you! Instead, fork, edit and create a pull request.

This is a public service based on collaborative efforts, maintained in spare time on voluntary basis.

# Eligible Resources Types

The following type of resources are eligible for inclusion in this project:

1. [Source code]
2. [Tutorials]
3. [Books and courses]
4. [Libraries and tools]

## Source Code

Source code resources fall under three categories:

1. PureBasic code projects.
2. PureBasic snippets.
3. Code projects in other languages which are usable from within PureBasic language or IDE (libraries, tools, etc.).

All code resources must meet the following criteria:

1. Must bare an open-source license.
2. Must be publicly available via a VCS/SCM service like [GitHub], [GitHubGist], [GitLab], [ChiselApp], etc.

Links to ZIP archives or "pasted code" _will not_ be included in this project ([read further to learn why]).

Links to source code without an explict open source license _will not_ be included in this project, even if the author published it publicly (for example, on the [PureBasic Forum]).

## Tutorials

Links to PureBasic-related tutorials must meet the following criteria:

1. Must be free to read.
2. Must not require any form of registration to be fully viewable.
3. Must be legitimately published.

Tutorials don't need to be open source, as long as they can be freely and lawfully read online from a legitimate source (website, forum, etc.).

## Books and Courses

Links to commercial PureBasic-related books and courses are eligible for inclusion in the project, as long as the link points to a trusted source and legitimate seller.

## Libraries and Tools

Links to commercial PureBasic libraries and tools are eligible for inclusion, provided that the product is actively maintened, supports the latest PureBasic version and the link points to a trusted source and legitimate seller.

Products which are not actively maintained may be linked only if a disclaimer is provided with the link, clarifying which version of PureBasic the product works with; but the maintainer of this project might reject such links at his sole discretion.

# FAQ

Answers to frequently asked questions...

## Why Version-Control?

> Links to ZIP archives or "pasted code" _will not_ be included in this project.

If you would like to see unversioned resources included in this list, make them Awesome by creating a repository or a [Gist] out of them first (that's what open-source is all about, after all). We'd rather promote a repository created by a third party than a link to pasted code or a ZIP archive by the original author (although we would provide a backlink to the original code/author in this case).

You may ask, "Why?"

The aim of this list is to promote a collaborative environment where users have the freedom to proactively participate in code developement, without having to struggle to keep their codebase up to date. We'd like this list to become a trusted source of reference for collaborative code resources, and in order to achieve this we need to draw a clear line between usable and unusable resources. Hence the choice to focus on version controlled code projects only.

Experience from the [PureBasic forum] has shown that "code pasting" and ZIP archives tend to be short lived. The original author often doesn't have the time/need to keep the codebase updated to the latest PureBasic version, and attempts to keep the code alive by third parties end up creating a long sequence of additional posts/threads and/or externally linked ZIP files which are difficult to keep track of — and too often the external links to ZIP files soon become dead links.

The PureBasic community is not huge, and in order to keep code alive across PureBasic version updates it's fundamental to adopt a community-oriented approach to code maintainance, where each user can easily contribute to the original codebase in a non-disruptive manner, and trying to avoid the profileration of multiple disconnected variations of the same codebase. That's what version control and good coding practices are all about.

When you use third party code in your own projects, and the original (upstream) code is updated, unless you are using some version control system you'll end up having to manually copy and paste the changed files from the original project to your own — and if you had changed the actual source files you'll have to manually reintroduce your changes at each and every update, one by one, over and over again. No wonder that such an approach soon leads to abbdandoned code — no matter how good the original code was, it's just to troublesome to keep up with.

Nevertheless, if (against all odds) you feel more comfortable collaborating at projects by pasting source code in endless thread posts, and then manually integrating these canges via copy and paste operations back-and-forth between a webpage and the editor, you should use the [PureBasic Forum] instead, where this practice seems still widespread and commonly accepted.

On the other hand, if you think that life is too short to waste it endlessly copying-&-pasting in isolation when there's a pletora of dedicated free cooperative tools that can handle changes-integration for you, then you're better off publishing your favourite code on GitHub, and let others help you keep it alive. In the latter case, this list might help you find other projects and users and give visibility to your own projects.

## On Publicly Available Code Without License

> Links to source code without an explict open source license _will not_ be included in this project, even if the author published it publicly (for example, on the [PureBasic Forum]).

You will often find code snippets (or whole projects) published on PureBasic Forum by their authors. It might be tempting to assume that this if free and open-source code, but unless the author has explicitly stated so that is not the case.

Unless an author states that his/her code may be freely reused by others (by a clear statement to that extent, or by releasing it under a known FOSS license) we have to assume that the code is copyrighted and not reusable. The mere fact that an author has publicly disclosed some source code doesn't imply it can be used by others — the author intention might be that of providing a practical example during a discussion, or he/she might be publishing some code to seek advice on its developement.

When in doubt, always ask the original author for permission before redistributing his/her code or utilizing it in your own project.

<!-----------------------------------------------------------------------------
                               REFERENCE LINKS                                
------------------------------------------------------------------------------>

<!-- In-Doc Cross References -->

[Books and courses]: #books-and-courses "Jump to document section"
[Libraries and tools]: #libraries-and-tools "Jump to document section"
[read further to learn why]: #why-version-control
[Source code]: #source-code "Jump to document section"
[Tutorials]: #tutorials "Jump to document section"

<!-- PB Links -->

[Awesome PureBasic]: https://github.com/tajmone/awesome-purebasic "Visit the Awesome PureBasic repository"
[PureBasic Forum]: https://www.purebasic.fr/english/
[PureBasic]: https://www.purebasic.com/ "Visit PureBasic official website"
[SpiderBasic]: https://www.spiderbasic.com/ "Visit SpiderBasic official website"

<!-- VCS Services -->

[ChiselApp]: http://chiselapp.com/ "Visit ChiselApp"
[GitHub]: https://github.com "Visit GitHub"
[GitHubGist]: https://gist.github.com/ "Visit GitHubGist"
[GitLab]: https://gitlab.com "Visit GitLab"

<!-- References -->

[Gist]: https://help.github.com/articles/about-gists/ "Learn more about code Gists..."

<!-- EOF -->