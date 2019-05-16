![logo](docs/images/logo/Genesis.png)

> What: Monolith of related generator building blocks
> 
> Why: Ease the pain associated with creating boilerplates
> 
> Who: This repo ("GENESIS") is intended for maintainers of these boilerplates.  If you're seeking to use any of the boilerplates, I recommend using them individually as needed. You'll find links and descriptions below 

## Getting Started

After cloning this repo, run the following inside this directory:

```bas**h**
npx repogen .repogen.js
```

You only need to run repogen once. After that, you can continue using the repositories individually as you would.


### Active - `Maintained`
| Effort Level (:boom:/4)  | Code Name | Name                                                                   | Description                                                             |
|:-------------------------|:----------|:-----------------------------------------------------------------------|:------------------------------------------------------------------------|
| :boom::boom:             | `AGEN`    | [alpha-genesis](https://github.com/servexyz/alpha-genesis)             | Shim for LGEN, FGEN and CGEN                                            |
| :boom::boom:             | `FGEN`    | [file-genesis](https://github.com/servexyz/file-genesis)               | File generator                                                          |
| :boom::boom::boom:       | `CGEN`    | [content-genesis](https://github.com/servexyz/content-genesis)         | Content generator                                                       |
| :boom::boom::boom:       | `LGEN`    | [library-genesis](https://github.com/servexyz/library-genesis)         | Library generator                                                       |
| :boom::boom:             | `LGENC`   | [library-genesis-cli](https://github.com/servexyz/library-genesis-cli) | Library generator  CLI                                                  |
| :boom::boom::boom::boom: | `RGEN`    | [repo-genesis](https://github.com/servexyz/repo-geneis)                | Clone symlinked repos to make flexible monoliths without git submodules |
| :boom::boom::boom:       | `RGENC`   | [repo-genesis-cli](https://github.com/servexyz/repo-genesis-cli)       | Monolith maker CLI                                                      |

### Active - `Helpers`
| Effort Level | Name                                                                           | Description        |
|:-------------|:-------------------------------------------------------------------------------|:-------------------|
| :boom:       | [library-genesis-example](https://github.com/servexyz/library-genesis-example) | Demonstrating LGEN |