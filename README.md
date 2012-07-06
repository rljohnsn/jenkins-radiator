## Jenkins CI Radiator

A small backbone.js application that monitors your Jenkins CI build server and displays failing, passing, building and disabled jobs. Audio is played when jobs move from a passing state to a failing state or from a failing state to a passing state.

### Configuration

1. Edit `config.js` and update the `ci_json_url` to point to your Jenkins instance
2. Open `index.html` in Chrome or Safari

### Optional Configuration

* Edit `config.js` and set the `refresh_interval` to something other than 1 minute

### Screenshots

__Failing Builds__
![Failing Builds in Jenkins Radiator](https://dl.dropbox.com/u/14820/jenkins-radiator-failing.png)

__Passing Builds__
![Passing Builds in Jenkins Radiator](https://dl.dropbox.com/u/14820/jenkins-radiator-passing.png)