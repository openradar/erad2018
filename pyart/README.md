## Hands on Py-ART
In this session, the Python ARM Radar Toolkit (Py-ART) package will be explored. For more information, including examples and developer and user documentation, visit  <https://arm-doe.github.io/pyart/>.

This session will first show how to read a radar file and explore the radar object that is created from reading the radar file. Also in this session, we will learn how to plot radar data using Py-ART, how to modify the data in the radar object and how to create a new radar file from the radar object.

For this session, you should have the [open virtual machine](http://openradarscience.org/vm-docs/) up and running on your system.
The Py-ART Jupyter notebooks are accessible on your VM instance by starting the Jupyter server:

```
$ ./start_notebook.sh openradar
```

Then navigate with your host system's browser to [http://127.0.0.1:8888/tree](http://127.0.0.1:8888/tree), and open the directory `pyart_short_course` and start the notebook `1_pyart_reading_and_plotting_data.ipynb` from the list. We'll take it from there...
