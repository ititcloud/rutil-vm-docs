# ititcloud.github.io

> 아이티클라우드 (개발팀) 블로그

## What's included?

![shield-react][shield-react]
![shield-node][shield-node]

## 🚀Quickstart

> [!TIP]
> ### Docusaurus
> 
> ```sh
> npm run start                          # Docusaurus 블로그 기동 (개발용)
> npm run build                        # Docusaurus 결과물 생성
> ```

### Deployment

Using SSH:

```sh
USE_SSH=true yarn deploy
```

Not using SSH:

```sh
GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

[shield-proj-v]: https://img.shields.io/github/package-json/v/chanhi2000/devlog?style=flat-square
[shield-license-gpl]: https://img.shields.io/github/license/chanhi2000/devlog?style=flat-square
[shield-github-action]: https://github.com/chanhi2000/devlog/actions/workflows/vuepress-deploy.yml/badge.svg
[shield-react]: https://img.shields.io/badge/react-3.4.x-4FC08D?logo=react&logoColor=4FC08D&style=flat-square
[shield-node]: https://img.shields.io/badge/node.js-18.12.x-339933?logo=nodedotjs&logoColor=339933&style=flat-square