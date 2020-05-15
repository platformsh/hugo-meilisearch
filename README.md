# hugo-meilisearch

## About

This is not a standalone theme. It is a [Hugo](https://gohugo.io) theme component providing a the generation of a search index suitable for indexing with the awesome [MeiliSearch](https://www.meilisearch.com/). An open source, blazingly fast and hyper relevant search-engine that will improve your search experience. 

## Usage

1. Add the `hugo-meilisearch` as a submodule to be able to get upstream changes later `git submodule add https://github.com/platformsh/hugo-meilisearch themes/hugo-meilisearch`
2. Add `hugo-meilisearch` as the left-most element of the `theme` list variable in your site's or theme's configuration file `config.yaml` or `config.toml`. Example, with `config.yaml`:
    ```yaml
    theme: ["hugo-meilisearch", "my-theme"]
    ```
    or, with `config.toml`,
    ```toml
    theme = ["hugo-meilisearch", "my-theme"]
    ```

### Credits

Copyright © 2020 onwards, Chad Carlson, Nick Andregg, Ori Pekelman @platform.sh

Thanks to
- [Nicolas Martignoni](https://github.com/martignoni) for the approach I am borrowing