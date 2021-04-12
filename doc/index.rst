Daktilograf STT
=========

**Daktilograf STT** je deep-learning za trening i transkripciju glasovnih modela u tekstualne (speech-to-text).

Daktilograf STT je detaljno testiran kako za razvojnu tako i za produkcionu upotrebu 🚀


.. toctree::
   :maxdepth: 1
   :caption: Quick Reference

   DEPLOYMENT

   TRAINING_INTRO

   BUILDING

Brza instalacija: Instalacija
^^^^^^^^^^^^^^^^^^^^^^

Najbrzi nacin instalacije Daktilograf STT modela je instalacija upotrebom `pip` komande iz Python 3.5 ili novijeg paketa (*Upozorenje - samo linux podrska za sad. Radimo na uspostavljanju modula za druge operativne sisteme.*): 

.. code-block:: bash

   # Kreirajte i aktivirajte virtuelno okruzenje
   $ python3 -m venv daktilograf-stt
   $ source daktilograf-stt/bin/activate

   # Instalirajte Daktilograf STT
   $ python3 -m pip install -U pip
   $ python3 -m pip install stt

   # Preuzmite Daktilograf STT istrenirane jezicke modele (Linkovi ce vam biti dostupni logovanjem na daktilograf.me/login)
   $ curl -LO https:...
   $ curl -LO https:...

   # Preuzmite semplove audio snimaka (Linkovi ce vam biti dostupni logovanjem na daktilograf.me/login)
   $ curl -LO https:...
   $ tar -xvf audio-test.tar.gz

   # Transkribujte audio fajl
   $ stt --model daktilograf-en.pbmm --scorer daktilograf-en.scorer --audio audio/2830-3980-0043.wav

.. toctree::
   :maxdepth: 1
   :caption: API Reference

   Error-Codes

   C-API

   DotNet-API

   Java-API

   NodeJS-API

   Python-API

.. toctree::
   :maxdepth: 1
   :caption: Examples

   Python-Examples

   NodeJS-Examples

   C-Examples

   DotNet-Examples

   Java-Examples

   HotWordBoosting-Examples

   Contributed-Examples

.. toctree::
   :maxdepth: 1
   :caption: Language Model

   LANGUAGE_MODEL

.. include:: SUPPORT.rst

.. toctree::
   :maxdepth: 1
   :caption: STT Playbook

   playbook/README

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
