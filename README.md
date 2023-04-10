# Tasmania 2018

We returned back to Tasmania on 1-5 May 2018 and mainly visited the [Freycinet National Park](http://www.parks.tas.gov.au/index.aspx?base=336) and Hobart. Although I had sprained my left patellar tendon a few weeks prior to the trip, I was able to walk around without too much difficulty by the time we arrived at Tasmania (thank goodness). The trip was really enjoyable and we were very lucky because a week later Hobart was deluged by wild weather and strong rains and Macquarie St (where we stayed) was flooded!

## 🚀 Project Structure

Inside this project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   │   └── image.jpg
│   ├── components/
│   │   └── Card.astro
│   ├── content/
│   │   └── article.md
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

In addition, each trip will be stored as a separate repository in the
`travelens` organization. This project integrates all the individual
repositories into a single seamless website.

## 🧞 Commands

`yarn` is used as a package manager
All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `yarn`          | Installs dependencies                            |
| `yarn dev`          | Starts local dev server at `localhost:3000`      |
| `yarn build`        | Build your production site to `./dist/`          |
| `yarn preview`      | Preview your build locally, before deploying     |
| `yarn astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `yarn astro --help` | Get help using the Astro CLI                     |
