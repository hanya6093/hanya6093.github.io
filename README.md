<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# GitHub Pages

_Create a site or blog from your GitHub repositories with GitHub Pages._

</header>

<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: previous version checked for empty pull request, changed to the correct theme `minima`.
-->

## Step 2: Configure your site

_You turned on GitHub Pages! :tada:_

We'll work in a branch, `my-pages`, that I created for you to get this site looking great. :sparkle:

Jekyll uses a file titled `_config.yml` to store settings for your site, your theme, and reusable content like your site title and GitHub handle. You can check out the `_config.yml` file on the **Code** tab of your repository.

We need to use a blog-ready theme. For this activity, we will use a theme named "minima".

### :keyboard: Activity: Configure your site

1. Browse to the `_config.yml` file in the `my-pages` branch.
1. In the upper right corner, open the file editor.
1. Add a `theme:` set to **minima** so it shows in the `_config.yml` file as below:
   ```yml
   theme: minima
   ```
1. (optional) You can modify the other configuration variables such as `title:`, `author:`, and `description:` to further customize your site.
1. Commit your changes.
1. (optional) Create a pull request to view all the changes you'll make throughout this course. Click the **Pull Requests** tab, click **New pull request**, set `base: main` and `compare:my-pages`.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
<div align="center">

  # Chirpy Jekyll Theme

  A minimal, responsive, and feature-rich Jekyll theme for technical writing.

  [![Gem Version](https://img.shields.io/gem/v/jekyll-theme-chirpy?color=brightgreen)][gem]&nbsp;
  [![CI](https://github.com/cotes2020/jekyll-theme-chirpy/actions/workflows/ci.yml/badge.svg?branch=master&event=push)][ci]&nbsp;
  [![Codacy Badge](https://app.codacy.com/project/badge/Grade/4e556876a3c54d5e8f2d2857c4f43894)][codacy]&nbsp;
  [![GitHub license](https://img.shields.io/github/license/cotes2020/jekyll-theme-chirpy.svg)][license]&nbsp;
  [![996.icu](https://img.shields.io/badge/link-996.icu-%23FF4D5B.svg)](https://996.icu)

  [**Live Demo →**][demo]

  [![Devices Mockup](https://chirpy-img.netlify.app/commons/devices-mockup.png)][demo]

</div>

## Features

<details>
  <summary>Click to expand/close details</summary>
  &nbsp;

- Dark / Light Theme Mode
- Localized UI language
- Pinned Posts on Home Page
- Hierarchical Categories
- Trending Tags
- Table of Contents
- Last Modified Date
- Syntax Highlighting
- Mathematical Expressions
- Mermaid Diagrams & Flowcharts
- Dark / Light Mode Images
- Embed Videos
- Disqus / Giscus / Utterances Comments
- Built-in Search
- Atom Feeds
- PWA
- Google Analytics
- SEO & Performance Optimization

</details>

## Documentation

To learn how to use, develop, and upgrade the project, please refer to the [Wiki][wiki].

## Contributing

Contributions (_pull requests_, _issues_, and _discussions_) are what make the open-source community such an amazing place
to learn, inspire, and create. Any contributions you make are greatly appreciated.
For details, see the "[Contributing Guidelines][contribute-guide]".

## Credits

This project was built primarily with the [Jekyll][jekyllrb] ecosystem,
[Bootstrap][bootstrap], [Font Awesome][icons], and some other [wonderful tools][lib].
The avatar and favicon design from [Clipart Max][image].

Many thanks to the [contributors][contributors] who participated in the development
and to the folks who reported bugs or shared ideas.

Last but not least, thanks to [JetBrains][jetbrains] for providing the _Open Source License_.

## Sponsoring

If you like this project or have built something through it, please consider sponsoring it, and your support would be greatly appreciated.

[![Ko-fi](https://img.shields.io/badge/Support_Me_on_Ko--fi-ff5e5b?logo=ko-fi&logoColor=white)][ko-fi]&nbsp;
[![Wechat Pay](https://img.shields.io/badge/Support_Me_on_WeChat-brightgreen?logo=wechat&logoColor=white)][donation]&nbsp;
[![Alipay](https://img.shields.io/badge/Support_Me_on_Alipay-blue?logo=alipay&logoColor=white)][donation]

## License

This project is published under [MIT License][license].

[gem]: https://rubygems.org/gems/jekyll-theme-chirpy
[ci]: https://github.com/cotes2020/jekyll-theme-chirpy/actions/workflows/ci.yml?query=event%3Apush+branch%3Amaster
[codacy]: https://app.codacy.com/gh/cotes2020/jekyll-theme-chirpy/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade
[license]: https://github.com/cotes2020/jekyll-theme-chirpy/blob/master/LICENSE
[jekyllrb]: https://jekyllrb.com/
[bootstrap]: https://getbootstrap.com/
[icons]: https://fontawesome.com/
[image]: https://www.clipartmax.com/middle/m2i8b1m2K9Z5m2K9_ant-clipart-childrens-ant-cute/
[demo]: https://cotes2020.github.io/chirpy-demo/
[wiki]: https://github.com/cotes2020/jekyll-theme-chirpy/wiki
[contribute-guide]: https://github.com/cotes2020/jekyll-theme-chirpy/blob/master/docs/CONTRIBUTING.md
[contributors]: https://github.com/cotes2020/jekyll-theme-chirpy/graphs/contributors
[lib]: https://github.com/cotes2020/chirpy-static-assets
[jetbrains]: https://www.jetbrains.com/?from=jekyll-theme-chirpy
[ko-fi]: https://ko-fi.com/coteschung/
[donation]: https://sponsor.cotes.page/
