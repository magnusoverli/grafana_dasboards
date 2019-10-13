# Grafana dashboards

## Introduction

This is a repo for my grafana dashboards. I use grafana to visualise data captured and created by Home Assistant. I use HA throughout my house, but the dashboards mostly focus on energy/consumption oriented data. 
From HA, the data has two possible routes to grafana:
##### 1:
HA can write data directly to an InlfuxDB that runs as an add-on in hassio. Grafana can then use that DB as a datasource.
##### 2:
I run Node-Red as an add-on in hassio. Node-Red is integrated with HA and can also manipulate and write data to another InfluxDB for Grafana to use.

The dashboard "Forbruk" is my first publicly shared dashboard, and consumes data manly from the Node-Red integration. It focuses on short-term historic data on electrical consumption in our household and also tries to give a visual break-down on the distribution of electrical consumtption per device and/or theme.
