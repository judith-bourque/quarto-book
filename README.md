
<!-- README.md is generated from README.Rmd. Please edit that file -->

# quarto-book

<!-- badges: start -->
<!-- badges: end -->

Demo of Quarto book published on Quarto Pub

The book is available online at
[judith-bourque.quarto.pub/quarto-book](https://judith-bourque.quarto.pub/quarto-book/)

## Create the book

1.  [Create a book using Quarto](https://quarto.org/docs/books/)

2.  Push book to GitHub repo

3.  [Publish a Quarto book on Quarto
    Pub](https://quarto.org/docs/publishing/quarto-pub.html)

4.  Add `/_book/` to `.gitignore`

5.  [Set up
    renv](https://quarto.org/docs/publishing/quarto-pub.html#prerequisites)
    with `renv::init()`

6.  [Protect main
    branch](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/managing-a-branch-protection-rule)

## Update book website

1.  Update renv with `renv::snapshot()`

2.  In your terminal, run `quarto publish quarto-pub`

## Notes

**Publishing on Quarto Pub:**

> “Quarto Pub sites are publicly visible, can be no larger than 100 MB
> and have a softlimit of 10 GB of bandwidth per month. If you want to
> authenticate users, host larger sites, or use a custom domain,
> consider using a professional web publishing service like Netlify
> instead.”
> ([source](https://quarto.org/docs/publishing/quarto-pub.html#overview))

**Rendering with GitHub Action:** Quarto books can be [automatically
rendered with each push to main using GitHub
Action](https://quarto.org/docs/publishing/quarto-pub.html#github-action),
but the technical needs outweigh the benefits as of writing this. For
examples of encountered issues, see
[judith-bourque/quarto-pub](https://github.com/judith-bourque/quarto-pub)
and
[judith-bourque/quarto-pub-2](https://github.com/judith-bourque/quarto-pub-2).
