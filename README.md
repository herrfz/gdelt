This just replicates some other Python based analyses on the <a href="http://eventdata.psu.edu/data.dir/GDELT.html">GDELT data</a>, for example the one by David Masad <a href="http://nbviewer.ipython.org/urls/raw.github.com/dmasad/GDELT_Intro/master/Getting_Started_with_GDELT.ipynb">here</a>, but using <a href="https://pypi.python.org/pypi/ipython-sql">%sql magic for IPython</a> and <a href="http://pandas.pydata.org">pandas</a>.

Eventually there will be a MySQL front-end provided on the data website, so that you don't have to download all of the data in the first place.

Download the MySQL table <a href="http://ge.tt/7vOP2Xf/v/0?c">here</a> (687 MB compressed, ca. 5.5 GB uncompressed). You need MySQL server running and Python's MySQLdb package to use the IPython notebook. Extract the file Events.sql.gz and import the table:

    $ mysql -u yourusername -p -D yourdbname < Events.sql

Here's the nbviewer link to the notebooks:

* <a href="http://nbviewer.ipython.org/urls/raw.github.com/herrfz/gdelt/master/israel_palestine.ipynb">Getting started</a>
