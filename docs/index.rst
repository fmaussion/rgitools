
rgitools: processing files from the Randolph Glacier Inventory
--------------------------------------------------------------

`rgitools <https://github.com/OGGM/rgitools>`_ provides several tools to
(pre-)process and analyse the glacier outlines provided by the
`Randolph Glacier Inventory <https://www.glims.org/RGI/>`_ (RGI).

It is currently in development, but our goal is to provide the following
sevices to the RGI community:

- **automated data quality check**: see :ref:`tools.qc`.
- **Geometry of the ice divides and listing or glacier clusters**:
  see :ref:`tools.intersects`.
- **Merging of glacier clusters**: see :ref:`tools.merge`.
- **Glacier hypsometry**: see :ref:`tools.hypso`.
- **ID link list between RGI versions** (not available yet)


Documentation
-------------

.. toctree::
    :maxdepth: 1

    whats-new
    installing
    tools
    known-issues
    dems
    api


Get in touch
------------

- View the source code `on GitHub`_.
- Report bugs or share your ideas on the `issue tracker`_.
- Improve the model by submitting a `pull request`_.
- Follow us on `Twitter`_.
- Or you can always send us an `e-mail`_ the good old way.

.. _e-mail: https://mailman.zfn.uni-bremen.de/cgi-bin/mailman/listinfo/oggm-users
.. _on GitHub: https://github.com/OGGM/rgitools
.. _issue tracker: https://github.com/OGGM/rgitools/issues
.. _pull request: https://github.com/OGGM/rgitools/pulls
.. _Twitter: https://twitter.com/OGGM1


About
-----

:Tests:

    .. image:: https://travis-ci.org/OGGM/rgitools.svg?branch=master
        :target: https://travis-ci.org/OGGM/rgitools
        :alt: Linux build status

:Documentation:

    .. image:: https://readthedocs.org/projects/rgitools/badge/?version=latest
        :target: http://rgitools.readthedocs.org/en/latest/?badge=latest
        :alt: Documentation status

:Authors:

    `Fabien Maussion <https://fabienmaussion.info/>`_,
    Johannes Landmann
