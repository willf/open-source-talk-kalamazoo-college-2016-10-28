# Open Source Class Presentation: GitHub Flow

Will Fitzgerald  
October 28, 2016  
2:45  Olds/Upton 312, Kalamazoo College

## Self introduction

- [ ] [Me](https://github.com/willf)

## Git Concept Basics

- [ ] Git gets easier once you understand branches are homeomorphic endofunctors mapping submanifolds of a Hilbert space – [Isaac Wolkerstorfer](https://twitter.com/agnoster/status/44636629423497217)
- [ ] (Can be) Distributed
- [ ] A repository (repo) is the "code", plus history (including branches)
- [ ] Branches are cheap, real cheap
- [ ] Most basic flow is: 
      - Clone (make a local copy)
        - Branch (work on a separate branch of the code)
        - Make changes
        - Add and commit (many times)
        - Merge to some branch (often `master`)
- [ ] The right "flow" will differ from work group to work group, no single holy grail

## GitHub Flow

- [ ] Simple process at use at GitHub
- [ ] [Illustrated Guide to GitHub Flow](https://guides.github.com/introduction/flow/)
- [ ] Two models
      - Fork & Pull Model (often used in open source contributions)
        - May need to keep up with the "upstream" repo [How to do this](https://gist.github.com/Chaser324/ce0505fbed06b947d962)
      - Shared Repository Model (often used for teams)

## Example

- [ ] Fork & Pull the [Spoon-Knife](https://github.com/octocat/Spoon-Knife) repo
      - [ ] Fork
      - [ ] Since it's a fork we can work on "master"
      - [ ] Make changes/add/commit
      - [ ] Make pull request
 - [ ] Shared repository
       - [ ] Branch
       - [ ] Since it's a fork we can work on "master"
       - [ ] Make changes/add/commit
       - [ ] Make pull request

## More resources
- [ ] `hub` command (Wraps `git` for GitHub-based repository)
