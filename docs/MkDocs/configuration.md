# Configure
## Project layout
    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
## mkdocs.yml - file example
    site_name: OK Notebook 
    site_url: https://ori-kruk.github.io/ # must have the trailing slash

    theme:
        name: material
        features:
            - navigation.instant
            - navigation.tracking
            - navigation.tabs
            - navigation.sections

    markdown_extensions:
        - admonition
        - pymdownx.details
        - pymdownx.superfences
        - pymdownx.highlight:
            anchor_linenums: true
        - pymdownx.inlinehilite
        - pymdownx.snippets
        - pymdownx.superfences    