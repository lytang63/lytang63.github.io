# Luyao Tang (唐路垚) — Academic Homepage

This repository contains the source code for my academic homepage:

**[https://lytang63.github.io](https://lytang63.github.io)**

I am a Ph.D. student in Electrical and Electronic Engineering at The University of Hong Kong. My research focuses on computer vision and machine learning, with particular interests in open-world learning, object-centric learning, generalized category discovery, out-of-distribution generalization, foundation models, visual reasoning, and AI for healthcare.

## Homepage Content

The website presents:

- research interests and recent news;
- selected honors and a detailed awards record;
- publications with paper, project, and code links;
- education and teaching experience;
- academic service and reviewing activities.

## Updating the Website

The main homepage content is maintained in [`_pages/about.md`](_pages/about.md). Site metadata and profile links are configured in [`_config.yml`](_config.yml), navigation items are stored in [`_data/navigation.yml`](_data/navigation.yml), and publication images are stored in [`images/`](images/).

To preview the website locally, install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

The local preview is available at `http://127.0.0.1:4000` by default.

## Acknowledgements

This website is built upon [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io), which is based on the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) Jekyll theme. The visual presentation and content have been customized for my academic profile.

## License

The website source is available under the terms described in [LICENSE](LICENSE).
