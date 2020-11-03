```bash
   ___ _                  _        __
  / __\ |__   __ _ _ __  (_) ___  / /  ___   __ _
 / /  | '_ \ / _' | '_ \ | |/ _ \/ /  / _ \ / _' |
/ /___| | | | (_| | | | || |  __/ /__| (_) | (_| |
\____/|_| |_|\__,_|_| |_|/ |\___\____/\___/ \__, |
                       |__/                 |___/

  v: 1.3.0 - https://github.con/sayjeyhi/chanjelog

flag  |  description
-----------------------------------------------------
-h    |  show help
-r    |  *{string} git repo url e.g: git.com/project.git
-f    |  {string} a file path to set version init with -s search format e.g: '/docker-compose.yml'
-s    |  {string} search pattern in version file e.g: '- DEPLOY_VERSION=[0-9]*\.[0-9]*\.[0-9]*'
-p    |  {string} search replace pattern in version file e.g: '- DEPLOY_VERSION='
-u    |  {string} jira tasks prefix to automaticly convery #[0-9]* to jira links in commit messages e.g: 'https://jira.site.com/browse/SP-'
-g    |  {boolean} to control adding tag on git or not e.g: [1|0]
-v    |  {string} to control version increase type e.g: ['patch'|'minor'|'major']
-c    |  {boolean} to control update changeslog.md file


You should have CI_USER and CI_ACCESS_TOKEN variables to allow ci to update your git.
---
An open source hack by @sayjeyhi - https://sayjeyhi.com with SemVer2.0.0
```
