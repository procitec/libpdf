.. _api:

API
===

Loading a PDF
-------------

.. automodule:: libpdf
    :members: load

Returned objects
----------------

.. autoclass:: libpdf.apiobjects.ApiObjects

.. autoclass:: libpdf.apiobjects.Flattened

Model classes
-------------

The object :class:`~libpdf.apiobjects.ApiObjects` returned by :func:`libpdf.load` contains the following
class (instances).

Root
~~~~

.. autoclass:: libpdf.models.root.Root

File
~~~~

.. autoclass:: libpdf.models.file.File

FileMeta
~~~~~~~~

.. autoclass:: libpdf.models.file_meta.FileMeta

Page
~~~~

.. autoclass:: libpdf.models.page.Page

Element
~~~~~~~

.. autoclass:: libpdf.models.element.Element

Chapter
~~~~~~~

.. autoclass:: libpdf.models.chapter.Chapter

Paragraph
~~~~~~~~~

.. autoclass:: libpdf.models.paragraph.Paragraph

Table
~~~~~

.. autoclass:: libpdf.models.table.Table

Cell
~~~~

.. autoclass:: libpdf.models.table.Cell

Figure
~~~~~~

.. autoclass:: libpdf.models.figure.Figure

Position
~~~~~~~~

.. autoclass:: libpdf.models.position.Position


Link
~~~~

.. autoclass:: libpdf.models.link.Link