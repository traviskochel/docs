Font examples
=============

Make monospaced font
^^^^^^^^^^^^^^^^^^^^

.. showcode:: roboFontExamples/fonts/monoMaker.py

Open font in layer
^^^^^^^^^^^^^^^^^^

.. showcode:: roboFontExamples/openFonts/openFontInLayer.py

Clean glyph names with quotes in groups
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

FontLab uses the single quote character ``'`` to indicate key glyphs in spacing groups. In RoboFont/UFO the concept of key glyphs does not exist. The script below cleans names of key glyphs in groups created with FontLab.

.. showcode:: roboFontExamples/fontGroups/changeGroupSingleQuote.py
