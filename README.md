# 21datalab
This project is an open source initiative for self-service analytics in industrial applications. It focusses on the collaboration between data scientists and expert users/operators. It will cover
* import and handling of data
* OPC-UA connectivity
* data modelling 
* API to implement machine learning
* microservice architecture
* interactive graphical widgets for simple self-service analytics
Further reading:
* project website: http://21data.io
* architecture: https://docs.google.com/document/d/1wRY5CCxqMQUc9PZoYwd0hGqGEIbNxXPm5Qt8GsjM-l8/edit?usp=sharing

# system requirements
The framework is prepared to run on edge, desktop or cloud and is a microservice architecure. The core software is based on python 3.6. Currently, only the source-code version is available
## setup
* install python 3.6, recommended https://www.anaconda.com/
* install bokeh 1.04 for python (e.g. pip install bokeh==1.0.4), use this exact version, work for 1.10 is ongoing
* prepare the web applications folder, it needs some more packages which are placed under web/modules:
  * web/modules/bootstrap (MIT License): get the latest bootstrap dist https://getbootstrap.com/, place it here directly 
  * web/modules/bootstrap-select/ (MIT License):https://developer.snapappointments.com/bootstrap-select/
  * web/modules/bootstrap-navbar-sidebar (MIT License): https://github.com/mladenplavsic/bootstrap-navbar-sidebar
  * web/modules/bootswatch (MIT License): https://github.com/thomaspark/bootswatch
  * web/modules/font-awesome/ (License: https://fontawesome.com/license/free) https://use.fontawesome.com/releases/v5.7.2/fontawesome-free-5.7.2-web.zip
  * web/modules/jquery/ (MIT License) https://jquery.com/download/
  * web/modules/jstree (MIT License) https://www.jstree.com/
  * web/modules/jsree-grid (MIT License) https://github.com/deitch/jstree-grid
  * web/modules/other contains:
    * popper.js (MIT License) https://popper.js.org/

## demo
* under windows: start the model rest services with "occupancydemo.bat" 
* goto http://localhost:6001/index.html
  * you'll find the model tree under the tab model  
  * you'll find the time UI under tab pipelines, then select the "occupancy" and open, it takes 10 seconds to load the UI
  * demo how to here: https://docs.google.com/document/d/1q7Ph-TBbDy314IkCoWfwP1www-dX2-i9EQaSTRKHtlc/edit?usp=sharing
  


