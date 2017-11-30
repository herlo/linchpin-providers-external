Provisioning
------------

This repository contains additional providers for the `linchpin <https://github.com/CentOS-PaaS-SIG/linchpin.git>`_ project.  Essentially, this repository can be cloned onto a system with linchpin already installed. Modifying the linchpin.conf and updating the `external_providers_path` with the new location will then make these additional providers available for use with linchpin.

Beaker
======

Provisions specific types of systems from an available catalog. See https://beaker-project.org/ for more detail about how Beaker works.

Reference:

* `<https://github.com/CentOS-PaaS-SIG/linchpin-providers-external/blob/master/library/bkr_server.py>`_
* `<https://github.com/CentOS-PaaS-SIG/linchpin-providers-external/blob/master/library/bkr_info.py>`_

Duffy
=====

Provisions preallocated CentOS 6 & 7 systems for Continuous Integration purposes.

Reference: https://wiki.centos.org/QaWiki/CI/Duffy

Requires: https://github.com/herlo/duffy-ansible-module added to the library path

Openshift
=========

Provisions containers from an Openshift endpoint. See https://docs.openshift.com/ for more detail about how Openshift works.

Reference: https://docs.ansible.com/ansible/2.4/oc_module.html

oVirt
=====

Provisions virtual machines using a web interface (or API) via the libvirtd daemon. See https://ovirt.org/ for more detail about how oVirt works.

Reference: http://docs.ansible.com/ansible/latest/list_of_cloud_modules.html#ovirt

Rackspace
=========

Rackspace is a specialized Openstack instance with commercial support. See https://www.rackspace.com/en-us/cloud for more detail about how Rackspace works.

Reference: http://docs.ansible.com/ansible/latest/list_of_cloud_modules.html#rackspace
