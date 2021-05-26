Create release with twine

- install twine "pip install twine"
- create sdist witgh "make sdist"
- Create file "$HOME/.pypirc" with config
- Upload the dist folder with twine "twine upload dist/*"


\[pypi\]
  username = __token__
  password = <pypi token>


.. image:: https://travis-ci.org/scanny/python-pptx.svg?branch=master
   :target: https://travis-ci.org/scanny/python-pptx

*python-pptx* is a Python library for creating and updating PowerPoint (.pptx)
files.

A typical use would be generating a customized PowerPoint presentation from
database content, downloadable by clicking a link in a web application.
Several developers have used it to automate production of presentation-ready
engineering status reports based on information held in their work management
system. It could also be used for making bulk updates to a library of
presentations or simply to automate the production of a slide or two that
would be tedious to get right by hand.

More information is available in the `python-pptx documentation`_.

Browse `examples with screenshots`_ to get a quick idea what you can do with
python-pptx.

.. _`python-pptx documentation`:
   https://python-pptx.readthedocs.org/en/latest/

.. _`examples with screenshots`:
   https://python-pptx.readthedocs.org/en/latest/user/quickstart.html
