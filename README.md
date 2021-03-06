koji - RPM building and tracking system
=======================================

Koji is an RPM-based build system. The Fedora Project uses Koji for
[their build system](http://koji.fedoraproject.org/koji/), as do
[several other projects](https://fedoraproject.org/wiki/Koji/RunsHere).

Koji's goal is to provide a flexible, secure, and reproducible way to build software.

Key features:

* New buildroot for each build
* Robust XML-RPC APIs for easy integration with other tools
* Web interface with SSL and Kerberos authentication
* Thin, portable command line client
* Users can create local buildroots
* Buildroot contents are tracked in the database
* Versioned data

Communicate
-----------

* Comments, questions, bugs, feedback, ideas, help requests? We'd love to hear from you.
* Mailing lists:
  * Development: [koji-devel AT lists.fedorahosted.org](https://lists.fedorahosted.org/mailman/listinfo/koji-devel)
  * User discussion and Fedora-specific topics: [buildsys AT lists.fedoraproject.org](https://admin.fedoraproject.org/mailman/listinfo/buildsys)
* IRC chat: #koji on irc.freenode.net

Bugs/RFEs
---------

If you have found a bug or would like to request a new feature, please [report an issue in Pagure](https://pagure.io/koji/issues).

Download
--------

The koji source code can be downloaded with git via:

    git clone https://pagure.io/koji.git

You may browse code at https://pagure.io/koji

Archived releases can be found at https://fedorahosted.org/released/koji/

Documentation
-------------

See: https://docs.pagure.org/koji/


Related Software
----------------

* [Mock](https://fedoraproject.org/wiki/Projects/Mock): The tool Koji uses to
  generate buildroots
* [Yum](http://yum.baseurl.org/)
* [Mash](https://git.fedorahosted.org/cgit/mash/)
