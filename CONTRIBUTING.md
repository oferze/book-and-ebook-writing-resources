## Contributor License Agreement
By contributing you agree to the [LICENSE](https://github.com/oferze/book-and-ebook-writing-resources/blob/master/LICENSE) of this repository.

## In a nutshell
1. You don't have to know git: if you found something of interest which is *not already in this repo*, please open an issue with your links propositions.
    - If you know git, please fork the repo and send pull requests.

2. Make sure to follow the [guidelines below](#guidelines).

### Guidelines
- If a resource is behind a registration page, please supply a direct link to the resource itself (be it a page, PDF file or anything else)
- always prefer a `https` link over a `http` one -- as long as they are on the same domain and serve the same content
- on root domains, strip the trailing slash: `http://example.com` instead of `http://example.com/`
- always prefer the shortest link: `http://example.com/dir/` is better than `http://example.com/dir/index.html`
    + no URL shortener links
- usually prefer the "current" link over the "version" one: `http://example.com/dir/book/current/` is better than `http://example.com/dir/book/v1.0.0/index.html`
- if a link has an expired certificate/self-signed certificate/SSL issue of any other kind:
  1. *replace it* with its `http` counterpart if possible (because accepting exceptions can be complicated on mobile devices)
  2. *leave it* if no `http` version but link still accessible through `https` by adding an exception to the browser or ignoring the warning
  3. *remove it* otherwise
- if a resource exists at different places on the Internet
    + use the link with the most authoritative source (meaning author's website is better than editor's website is better than third party website)
- prefer atomic commits (one commit by addition/deletion/modification) over bigger commits. No need to squash your commits before submitting a PR. (We will never enforce this rule as it's just a matter of convenience for the maintainers)

- Don't put spaces between `]` and `(`

```
BAD : * [Another Awesome Resource] (http://example.com/resource.html)
GOOD: * [Another Awesome Resource](http://example.com/resource.html)
```

- If you wish to mention the author, use ` - ` (a dash surrounded by single spaces)

```
BAD : * [Another Awesome Resource](http://example.com/resource.html)- John Doe
GOOD: * [Another Awesome Resource](http://example.com/resource.html) - John Doe
```

- Put a single space between the link and its format

```
BAD : * [Another Awesome Resource](http://example.com/resource.pdf)(PDF)
GOOD: * [Another Awesome Resource](http://example.com/resource.pdf) (PDF)
```

- Author comes before format:

```
BAD : * [Another Awesome Resource](http://example.com/resource.pdf)- John Doe
GOOD: * [Another Awesome Resource](http://example.com/resource.pdf) - John Doe (PDF)
```
