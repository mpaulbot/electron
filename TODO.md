# todo

- how to deploy idea 1
  - keep electron module as sub module
  - upgrade node to v12 to get electron-forge working
    - start with just this internal app?
  - build as part of main git repo actions
  - host private update server
- deploy #2
  - create public repo for electron module
  - as part of build process, simply download from public fetch urls
  - main repo triggers remote deploy actions + releases
    - https://blog.marcnuri.com/triggering-github-actions-across-different-repositories/
  - leverage free update/hosting options
  - more open source!
