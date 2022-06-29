### you are very welcome to Junior 

 I started learning JS at late 2020, when I had no Idea how big JS world is.
 Recently I figured out "JS is my Ninja way"! so I believe in teamwork and not giving up just like a Shinobi

Some Of My Skills: JS / HTML / CSS / TS / React / PHP





[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=fatemeKholousi)](https://github.com/anuraghazra/github-readme-stats)

<!--START_SECTION:waka-->
name: Waka Readme

on:
  workflow_dispatch:
  schedule:
    # Runs at every 12AM UTC
    - cron: "0 0 * * *"

jobs:
  update-readme:
    name: Update this repo's README
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
<!--END_SECTION:waka-->
