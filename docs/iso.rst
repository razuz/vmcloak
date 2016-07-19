ISO mode
==========

VMCloak has ability to deploy hosts also in ISO mode in order to make management of sandbox hosts using same platform.

In order to deploy host in ISO mode you should init the host with key ``--vm iso``. For example:

.. code-block:: bash

    vmcloak init --win7x64 win7-1 --iso-mount /srv/cuckoo/iso/win7/ 
    --ip 10.99.99.100 --gateway 10.99.99.1 --vm iso


Things to know
-----------------

* While using *iso* mode then starting the host should be done manually.
* For installing Office - make sure you enter the office CD to drive before launching  ``vmcloak install``
