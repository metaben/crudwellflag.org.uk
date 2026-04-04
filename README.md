# crudwellflag.org.uk

This is the source code for the Crudwell Flood Action Group website, built with the [Hugo](https://gohugo.io/) static site generator.

## Setup

1. install [git](https://github.com/git-guides/install-git), [go](https://go.dev/doc/install), and [Hugo](https://gohugo.io/).
2. clone this repository.

## Usage

Make all changes on a new branch.

### Layout

This website uses the [Stack](https://stack.cai.im/) theme, so it's worth reading the [documentation](https://stack.cai.im/) to know what styling and config is built-in.

### Content

Run `hugo new content content/blog/name-of-article-goes-here/index.md` to create an empty blog.

### Build, Test, Deploy

- Run `hugo serve` to test changes locally.
- (optional) Use [Dev Containers for VSCode](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) to re-build inside an isolated reproducible environment.
- If ok, commit and push changes, open a PR, and merge to main.
- A GitHub Actions workflow will automatically build and deploy the website.

## License

This project is dual-licensed under:

- Creative Commons [BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) - for content and assets (see [LICENSE](LICENSE)).
- MIT License - for code (see [LICENSE-CODE](LICENSE-CODE)).

## Credits

[Stack](https://stack.cai.im/) theme and [Starter template](https://github.com/CaiJimmy/hugo-theme-stack-starter) by Jimmy Cai.
