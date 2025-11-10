# gel-postgis

Currently ``make`` and the ``gen_ext_postgis.py`` script should be run
from inside an edgedb development venv.

To build, install, and test into a dev env:
- ``make``
- ``python scripts/gen_ext_postgis.py``
- ``make zip``
- ``edb load-ext postgis--3.5.1.zip``
- ``edb test tests/test_edgeql_postgis.py``
