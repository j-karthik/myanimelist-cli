## myanimelist-cli

myanimelist-cli is a minimalistic command line interface for fetching user anime data from [MyAnimeList](https://myanimelist.net/)

[![C/C++ CI](https://github.com/jmakhack/mya/actions/workflows/c-cpp.yml/badge.svg?branch=master)](https://github.com/jmakhack/mya/actions/workflows/c-cpp.yml)
[![CodeQL](https://github.com/jmakhack/mya/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/jmakhack/mya/actions/workflows/codeql-analysis.yml)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/a30e5356c06e4381a0b5ea92aba65ada)](https://www.codacy.com/gh/jmakhack/myanimelist-cli/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=jmakhack/myanimelist-cli&amp;utm_campaign=Badge_Grade)
[![Discord](https://img.shields.io/discord/1023562225790767175?color=%20%237289DA&label=discord&logo=discord&logoColor=%20%237289DA)](https://discord.gg/RTgxfFW9mS)<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-13-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

## Usage
```
$ mya --help
Usage: mya [OPTION...] [USERNAME]
Simple command line tool for fetching user anime data from MyAnimeList.

  -a, --all                  Fetch all anime for a user
  -c, --completed            Fetch a user's completed anime
  -d, --dropped              Fetch a user's dropped anime
  -h, --onhold               Fetch a user's on hold anime
  -p, --plantowatch          Fetch a user's plan to watch anime
  -w, --watching             Fetch a user's currently watching anime
  -s, --sfw                  Fetch only SFW anime
  -?, --help                 Give this help list
      --usage                Give a short usage message
  -V, --version              Print program version

Report bugs to <jmakhack@protonmail.com>.
```

## Example
```
$ mya -w jmak
watching 4 anime
1. Commit on Titan
2. JoJo's Bizarre Pull Request
3. My Neighbor Octocat
4. One Push Man
```

## Contributing
For info on how to contribute to myanimelist-cli, please refer to the [Contributing to the Project](CONTRIBUTING.md) document.

## Code of Conduct
myanimelist-cli is governed by the [Contributor Covenant v2.0](CODE_OF_CONDUCT.md).

## License
myanimelist-cli is licensed under the [MIT License](LICENSE).

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/jmakhack"><img src="https://avatars.githubusercontent.com/u/1442227?v=4?s=100" width="100px;" alt="jmakhack"/><br /><sub><b>jmakhack</b></sub></a><br /><a href="https://github.com/jmakhack/myanimelist-cli/commits?author=jmakhack" title="Code">💻</a> <a href="#maintenance-jmakhack" title="Maintenance">🚧</a> <a href="https://github.com/jmakhack/myanimelist-cli/commits?author=jmakhack" title="Documentation">📖</a></td>
      <td align="center"><a href="https://allcontributors.org"><img src="https://avatars.githubusercontent.com/u/46410174?v=4?s=100" width="100px;" alt="All Contributors"/><br /><sub><b>All Contributors</b></sub></a><br /><a href="https://github.com/jmakhack/myanimelist-cli/commits?author=all-contributors" title="Documentation">📖</a></td>
      <td align="center"><a href="https://www.linkedin.com/in/tim-beeren-88355615b/"><img src="https://avatars.githubusercontent.com/u/36151761?v=4?s=100" width="100px;" alt="Tim Beeren"/><br /><sub><b>Tim Beeren</b></sub></a><br /><a href="https://github.com/jmakhack/myanimelist-cli/commits?author=TBeeren" title="Tests">⚠️</a> <a href="https://github.com/jmakhack/myanimelist-cli/commits?author=TBeeren" title="Code">💻</a> <a href="https://github.com/jmakhack/myanimelist-cli/commits?author=TBeeren" title="Documentation">📖</a></td>
      <td align="center"><a href="https://vividhpandey.netlify.app/"><img src="https://avatars.githubusercontent.com/u/91251535?v=4?s=100" width="100px;" alt="Vividh Pandey"/><br /><sub><b>Vividh Pandey</b></sub></a><br /><a href="#maintenance-VividhPandey003" title="Maintenance">🚧</a></td>
      <td align="center"><a href="https://github.com/Nikhil-1503"><img src="https://avatars.githubusercontent.com/u/61755381?v=4?s=100" width="100px;" alt="Nikhil Shanbhag"/><br /><sub><b>Nikhil Shanbhag</b></sub></a><br /><a href="#maintenance-Nikhil-1503" title="Maintenance">🚧</a></td>
      <td align="center"><a href="https://adityaj7.github.io/"><img src="https://avatars.githubusercontent.com/u/42397096?v=4?s=100" width="100px;" alt="Aditya Jetely"/><br /><sub><b>Aditya Jetely</b></sub></a><br /><a href="#maintenance-AdityaJ7" title="Maintenance">🚧</a></td>
      <td align="center"><a href="https://muriloucolouco.github.io/"><img src="https://avatars.githubusercontent.com/u/58440129?v=4?s=100" width="100px;" alt="Murilo Leandro"/><br /><sub><b>Murilo Leandro</b></sub></a><br /><a href="https://github.com/jmakhack/myanimelist-cli/commits?author=MuriloucoLouco" title="Code">💻</a> <a href="#maintenance-MuriloucoLouco" title="Maintenance">🚧</a></td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/Sakshi-75"><img src="https://avatars.githubusercontent.com/u/20265098?v=4?s=100" width="100px;" alt="Sakshi Jain"/><br /><sub><b>Sakshi Jain</b></sub></a><br /><a href="https://github.com/jmakhack/myanimelist-cli/commits?author=Sakshi-75" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/features/security"><img src="https://avatars.githubusercontent.com/u/27347476?v=4?s=100" width="100px;" alt="Dependabot"/><br /><sub><b>Dependabot</b></sub></a><br /><a href="#maintenance-dependabot" title="Maintenance">🚧</a></td>
      <td align="center"><a href="https://www.linkedin.com/in/ahmedheltaher/"><img src="https://avatars.githubusercontent.com/u/42752070?v=4?s=100" width="100px;" alt="Ahmed Eltaher"/><br /><sub><b>Ahmed Eltaher</b></sub></a><br /><a href="https://github.com/jmakhack/myanimelist-cli/commits?author=ahmedheltaher" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/sameersecond"><img src="https://avatars.githubusercontent.com/u/101405993?v=4?s=100" width="100px;" alt="Sameer"/><br /><sub><b>Sameer</b></sub></a><br /><a href="https://github.com/jmakhack/myanimelist-cli/commits?author=sameersecond" title="Code">💻</a> <a href="https://github.com/jmakhack/myanimelist-cli/commits?author=sameersecond" title="Documentation">📖</a></td>
      <td align="center"><a href="https://portfolio-metaloopa.vercel.app/"><img src="https://avatars.githubusercontent.com/u/70171925?v=4?s=100" width="100px;" alt="Sudip Banerjee"/><br /><sub><b>Sudip Banerjee</b></sub></a><br /><a href="https://github.com/jmakhack/myanimelist-cli/commits?author=metal-oopa" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/The-Debarghya"><img src="https://avatars.githubusercontent.com/u/79015784?v=4?s=100" width="100px;" alt="Debarghya Maitra"/><br /><sub><b>Debarghya Maitra</b></sub></a><br /><a href="https://github.com/jmakhack/myanimelist-cli/commits?author=The-Debarghya" title="Code">💻</a> <a href="https://github.com/jmakhack/myanimelist-cli/commits?author=The-Debarghya" title="Documentation">📖</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
