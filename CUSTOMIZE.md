## How to customize?
* change the source code in `src` dir.
* change the theme color or choose you needed modules by editing `build-config.js`


## How to get updates from the original repository?
1. set the upstream, `git remote add upstream git@github.com:nolimits4web/swiper.git`
2. get their latest source code by running `git pull upstream master`
3. if any conflicts existed, fix them.


## How to use?
1. after your customize, rebuild by running `npm run build:prod`
2. push to `custom` branch or a new branch.
3. toggle to your project, add this package by running `yarn add <git remote url>#<branch/commit/tag>`
