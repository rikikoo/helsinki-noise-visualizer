# helsinki-noise-visualizer
A Python web app that visualizes open data received from sensors around Helsinki, Finland. 

## about
**WIP as of 2021-10-06**

Open data provided by [Forum Virium Helsinki](https://forumvirium.fi/en/tag/avoin-data-en/). Data is in the form of dB (decibels) per minute from 6 different sensors located in Helsinki.
helsinki-noise-visualizer scrapes and stores any new available data from https://iot.fvh.fi/opendata/noise/, and serves it to a web application that will visualize the data according to user-specified parameters, such as a rolling average time series with an arbitrary window, simultaneous comparison of different measurement points or time periods, etc.

