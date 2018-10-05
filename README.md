# Contently Open-source

A guide for Contently developers on how to approach open-sourcing internal projects.

## Our Projects

### Actively Maintained

- [Action mailer matchers](https://github.com/contently/action_mailer_matchers)
- [HTML diff service](https://github.com/contently/html-diff-service)
- [Videojs annotation comments](https://github.com/contently/videojs-annotation-comments)
- [xDomain cookies](https://github.com/contently/xdomain-cookies)

### No longer supported

- [Daisydiff](https://github.com/contently/daisydiff) (deprecated in favor of [HTML diff service](https://github.com/contently/daisydiff))

## Open-source policy

Open-source is encouraged whenever possible, but it is not the default policy, nor mandatory for any project. It is required that you get approval from a Director of Engineering before publishing your project.

### Getting approval

All projects need to be reviewed with a manager to determine open-source eligibility. The following statements must be true.

- The project does not contain technology that significantly differentiates the Contently product from competition.
- The code repository is free of any private information including personal data and private keys. (Use [these methods](https://help.github.com/articles/removing-sensitive-data-from-a-repository/) to remove private information from git history.)
- You are willing and have the time to perform the extra work required to create and maintain an open-source project, as outlined in [project quality](#project-quality).

### Project quality

One of the reasons that we are not open-source by default is this process requires extra responsibilities to be taken up by our developers. You are encouraged to work through the requirements listed below before publishing and to be responsive in replying to issues and pull requests on your project after publishing.

If any of these requirements cannot be met at the time of publishing, you can create Github issues for them, which can be taken up by you or other developers.

#### Quality requirements

- Thoroughly document how to interact with all APIs
    - Docs should go in depth with usage examples. A /docs directory can contain information beyond the README if necessary.
    - Use inline documentation to explain key areas of the code.
- Use semantic versioning
- Include the following files, which can be templated from this repo:
  - [README.md](templates/README.md)
  - [LICENSE](templates/LICENSE)
  - [CONTRIBUTING.md](templates/CONTRIBUTING.md)
  - [CHANGELOG.md](templates/CHANGELOG.md)

### Getting help from the team

You can encourage your teammates to help with your open-source project. It can be great to have help getting a code base ready for publishing by adding documentation, tests, or polishing APIs. You could also hand off writing blog posts about your project to a coworker who is interested.

### Licensing

By default, use the [MIT license](templates/LICENSE), which is included in this repo. Discuss with a Director of Engineering if you think a different license would be a better fit. For example, your project may be an extension of an existing open-source project which is under a different license.

### Process

1. Open a PR in this repo and use it to work through the following steps.
2. Review your repo with a Director of Engineering to get approval, based on [getting approval](#getting-approval).
3. Update your Github repo to be public, or create a new Github public repo.
4. Publish to any package managers, such as rubygems or npm, if necessary.
5. Merge your PR into contently/open-source.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Jack Pope** - *Initial work* - [@jackpope](https://github.com/jackpope)

See also the list of [contributors](https://github.com/contently/open-source/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* [@PurpleBooth](https://github.com/PurpleBooth) for the excellent README and CONTRIBUTING templates
* [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) for the excellent CHANGELOG template
