.. include:: cyverse_rst_defined_substitutions.txt

|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


STYLE TIPS - DELETE THIS PAGE BEFORE PUBLISHING
--------------------------------------------------

.. #### Comment: short description

Writing your documentation using sample data
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Where possible, you want write documentation instructions to be general enough
for users can follow along with their own data. To help do this, you can use
the **sample data admonition** to intersperse sample data-specific instructions
into your generic instructions.

To do this, start your documentation with a description and where possible,
a citation of the data:

     .. admonition:: Sample data

      **How to use provided sample data**

      In this guide, we will use an RNA-Seq dataset (*"Zika infected hNPCs"*).
      This experiment compared human neuroprogenetor cells (hNPCs)
      infected with the Zika virus to non-infected hNPCs. You can read more
      about the experimental conditions and methods
      `here <https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0175744>`_.
      Where appropriate, a note (in this orange colored background) in the
      instructions will indicate which options to select to make use of this
      provided dataset.

      **Sample data citation**: Yi L, Pimentel H, Pachter L (2017) Zika
      infection of neural progenitor cells perturbs transcription in
      neurodevelopmental pathways. PLOS ONE 12(4):
      e0175744. `10.1371/journal.pone.0175744 <https://doi.org/10.1371/journal.pone.0175744>`_

Then, as you have instructions, intersperse the sample data .. admonition


    1. First, enter the cutoff value for your dataset

        .. admonition:: Sample data

          *"Zika infected hNPCs"* dataset:

          Enter **30**

    2. Continue with next step...

    .. tip::
         If you don't see a desired species/genome `contact us <https://dnasubway.cyverse.org/feedback.html>`_ to have it added

    .. warning::
     When naming your samples and conditions, avoid spaces and special characters
     (e.g. !#$%^&/, etc.). Also be sure to be consistent with spelling.

Other admonitions
~~~~~~~~~~~~~~~~~~~
