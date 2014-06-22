startup
=======

###Objective:
- The documentation of setting up a full-stack collaborative development environment for a software project.
- Vagrant files to install essential tools in virtualbox.

###What do you need:
- Dev machines, Operating systems
- Domains
- Servers
    - Virtual Private Server (VPS)
    - Cloud computing platform
- Development tools
    - Langauge
        - C++, Java, Python, etc.
    - Development tool
        - make, maven, pybuilder, virtualenv, lint, etc.
    - IDE
        - Vim, Emacs, Eclipse, XCode, Visual Studio, etc.
    - Framework, SDK, libraries
        - Django, Jquery, Node.js, Andriod SDK, Hadoop, Protobuf, Google Maps API, etc.
    - Databases
        - RDBM or NoSQL
    - System tools
        - Memcached, Redis, RabbitMQ, Vagrant, etc.
    - Web server
        - Nginx or Apache
- Source code management system (SCM)
    - Git, Subversion
    - Code search
    - Code review
    - Code coverage
- Project management software
    - Agile development management
        - Planning and scheduling
        - Issue tracking
    - Document management
        - Twiki, Google Docs
    - [Comparison](http://en.wikipedia.org/wiki/Comparison_of_project_management_software)
- Continuous integration
    - Build, Test, Release
    - [Comparison](http://en.wikipedia.org/wiki/Comparison_of_continuous_integration_software)
- Deployment and Automation
    - Puppet, Chef, etc.


## Self-hosted Solutions

The below lists my choice for self-hosted development platform.

### Operating systems, virtual machines and cloud
- [Ubuntu 14.04 LTS](http://www.ubuntu.com)
    - A popular Linux distribution
- [Virtualbox](http://www.virtualbox.org)
    - Free VM software for all major platforms
- [Vagrant](http://www.vagrantup.com)
    - Vagrant allows you to share the vm images
- Virtual Private Server
    - [DigitalOcean](https://www.digitalocean.com/?refcode=0b59220c73df)
        - Easy to use, friendly for developers, as cheap as $5/month
    - [Linode](http://linode.com)
        - A leading VPS company.

### Source code management system
- [Git](http://git-scm.com)
    - A popular distributed SCM
    - [SourceTree](http://www.sourcetreeapp.com): A git GUI
    - Git tutorials
        - https://www.atlassian.com/git
- [GitLab](http://www.gitlab.com)
    - An alternative to github, open source, but hosted by yourself.
    - [DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-use-the-gitlab-one-click-install-image-to-manage-git-repositories) has a pre-installed vm image to setup a gitlab in a minute.

### Continuous Integration
- [Jenkins](http://jenkins-ci.org/)
    - A popular CI tool. Easy to install and use.


## Cloud-based solution:
- Cloud Computing Platforms
    - [OpenStack](http://openstack.org)
        - Open source cloud computing platform
    - [Amazon AWS](http://aws.amazon.com)
        - Market Leader
    - [Google Compute Engine](https://cloud.google.com/products/compute-engine) *
        - Made by Google
- [GitHub](http://www.github.com)
    - A popular git hosting service and developer's community
- [Atlassian](https://www.atlassian.com)
    - Pretty much everything you need for collaborative development enviornment
- [Thoughtworks](http://thoughtworks.com)
- Code review
    - http://gerrithub.io
