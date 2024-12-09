# OKai Contributors Site Generator

OK, creators of the [okai](https://github.com/okcashpro/okai) framework. This repo generates static sites showing GitHub contributor activity.


![okai_banner](https://github.com/okcashpro/okai/blob/main/docs/static/img/okai_banner.png?raw=true)

[Website](https://okcashpro.github.com/okai/): | [Discord](https://discord.gg/grvpc8c) | [Twitter/X](https://x.com/oktokencash) | [DAO](https://okdao.org/)


## Setup

1. Install dependencies:
```bash
npm install
```

2. Put your contributor data JSON files in the `data` directory

3. Build and generate the site:
```bash
npm run build
npm run generate
```

4. Open `profiles/index.html` to view the result

## Directory Structure

- `data/` - Place contributor JSON files here
- `scripts/` - Source code
- `dist/` - Built files
- `profiles/` - Generated static site

## Scripts

- `npm run build` - Bundle the site generator
- `npm run generate` - Generate the static site
