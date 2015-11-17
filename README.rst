|debops_logo| `DebOps Contrib <http://debops.org>`_
===================================================

.. |debops_logo| image:: http://debops.org/images/debops-small.png

**Additional Ansible roles of the DebOps project**

Welcome. This organization is meant to hold the Ansible roles and playbooks
that are not part of the official `DebOps <http://github.com/debops/>`_
project, but might be integrated with it in the future.

If you have any roles that you would like to add here, you can either create an
issue in this (``debops-contrib``) repository or contact the team at
``#debops`` IRC channel on FreeNode, or through the `mailing list
<https://groups.io/g/debops>`_.

Naming convention
-----------------

Roles are prefixed with an ``contrib-``. This was done because the `hyphen
should not be used normally`_.

When your role is ready you can ask @drybjed if he can upload it to `Ansible
Galaxy`_ under the name `debops.contrib-$your_role`.

..
 Local Variables:
 mode: rst
 ispell-local-dictionary: "american"
 End:

.. _`hyphen should not be used normally`: not be usedhttps://github.com/nickjj/ansigenome/pull/19#issuecomment-75597850
.. _`Ansible Galaxy`: https://galaxy.ansible.com/
