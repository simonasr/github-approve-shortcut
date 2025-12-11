# github-approve-shortcut
Chrome extension that binds `cmd+shift+x` to approve a PR

### Usage

On a Github PR page, press `cmd+shift+x` to approve the PR

### Installation

* Pull down this repo
* Visit: [chrome://extensions/](chrome://extensions/)
* Enable developer mode
* Click: `Load Unpacked`
* Browse to this repo and click `Select`

### Debugging

To enable debugging, execute the following:

`localStorage.setItem('github-approve-shortcut-debug', true)`

To disable debugging, execute the following:

`localStorage.setItem('github-approve-shortcut-debug', 'lol nope')`
