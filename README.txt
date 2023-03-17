Plugin Builder Results

Your plugin PipelinePlanner was created in:
    C:/projects/qgisTraining/PluginBuilder\pipeline_planner

Your QGIS plugin directory is located at:
    C:/Users/gq932f/AppData/Roaming/QGIS/QGIS3/profiles/default/python/plugins

What's Next:

  * Copy the entire directory containing your new plugin to the QGIS plugin
    directory

  * Compile the resources file using pyrcc5
    This is accomplished by:
    -using the OSGeo4W shell
    -Navigating to the project directory
    -Running the following command: 'pyrcc5 -o resources.py resources.qrc'
    -Copy the plugin from Dev Directory to QGIS plugin directory via pb:
        -in cmd of PyCharm: 'pbt deploy -y'

  * Run the tests (``make test``)

  * Test the plugin by enabling it in the QGIS plugin manager

  * Customize it by editing the implementation file: ``pipeline_planner.py``

  * Create your own custom icon, replacing the default icon.png

  * Modify your user interface by opening PipelinePlanner_dialog_base.ui in Qt Designer

  * You can use the Makefile to compile your Ui and resource files when
    you make changes. This requires GNU make (gmake)

For more information, see the PyQGIS Developer Cookbook at:
http://www.qgis.org/pyqgis-cookbook/index.html

(C) 2011-2018 GeoApt LLC - geoapt.com
