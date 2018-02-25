# Principles for Quality Code

This document sets out the standard to which inter-regional software development projects in SCORE will be held. It is versioned [in GitHub Releases](https://github.com/score-project/quality-code/releases) and [Issues/Bug Reports](https://github.com/score-project/quality-code/issues) and Pull Requests are welcome.

> The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](https://tools.ietf.org/html/rfc2119).

Projects MUST:

* have a `README` with a description of the codebases for the potential users/implementers
* explain in the `README` how to run, develop and build
* be developed in a public repository from the start
* provide a link to a public list of known issues and bugs
* allow non-contributors to post issues, bugs and suggested changes
* have documentation for all public APIs in the [OpenAPI standard](https://github.com/OAI/OpenAPI-Specification)
* have a `LICENCE` with an [Open Source Initiative designated "Popular License"](https://opensource.org/licenses/category) or [EUPL](https://eupl.eu/)

Projects SHOULD:

* kick ass
* have functional tests
* have a high level discription for (technical) management to understand in the `README`
* respond to incoming issues and change suggestions within a week
* provide contributors guidelines in a `CONTRIBUTING` file
* set up any tests to run in a public continuous integration environment
* have test and documentation code coverage to the highest degree possible
* have documented private APIs
* use a version number compatible with [Semantic Versioning](https://semver.org/)
* provide documentation on privacy and security
* contain configurations for automatic deployment and provisioning through systems such as OpenShift, Docker, Ansible, CloudForge etc

Projects MAY:

* publish a roadmap
* provide a forum or mailing list for discussion
* publish packages to relevant language specific repositories such as PyPi, Ruby Gems, NPM, Puppet Forge, etc
* provide a contribution and governance model in a `GOVERNANCE` file
* indicate the level of maintainance provided by whom and until when
* indicate a codebase/project status in the `README` that is one of: "Ideation"; "Alpha"; "Beta"; "Production"; "Archival"
* provide a list of contributors in a `CONTRIBUTORS` file
