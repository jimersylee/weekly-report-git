# weekly-report

This is an automated reporting tool for my job

# install

```js
npm install @foxtail/weekly-report-git
```

# usage

```js
foxrpt
```

# config

please edit the config file and provide your repositories directory and so on

```js
// ./config/index.js
module.exports = {
    username: 'username', // Git username
    password: 'password', // Git password
    reponame: 'origin', // Repository name
    dir: 'Git directory path', // /Users/viccici/github
    reportDir: 'Report directory path', // /Users/viccici/report
    commiter: {
        'Git name': 'Real name' // Git committer name matching the real name
    },
    projects: [
        {
            name: 'Project name', // We often use chinese project name
            folder: 'Project folder', // Git folder name that based on git path.  [ PS: weekly-report-git ]
            path: 'Git path'
        }
    ]
}
```
