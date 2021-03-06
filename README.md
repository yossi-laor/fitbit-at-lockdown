# FITBIT-at-LOCKDWON
Fitbit published analysis of behavioural changes through the lockdown -- less step count but more active minutes (see: https://blog.fitbit.com/lockdowns-lift-mobility-changes/). I am interested in my own data during the lockdown. As Swimming pools were shut down, my favourite activity of swimming and timing laps was impossible. As a substitute, I used Fitbit Inspire HR to time my activities (but I didn't use it otherwise). I bought this  activity tracker early April 2020 and I have now data for 365 days. I use the heart-rate json files to find out that I used the tracker 329 days, and did 412 activities of walking, cycling or workout. The most energetic ones were cycling intervals, but I didn't do this type of activity very often. I am happy to get comments, etc.  

The Jupyter notebooks:

JSON-to-DF  -- process the JSON files that Fitbit gives and creates 'activity' dataframes and summaries; these are stored as pickle files

Summary-plot -- plots some of the summary statistics of the activities

Heartrate-plot -- plots the full heart rate for some interesting activities

Interval-cycling -- analyses activities that include short cycles or intervals

Sandbox -- tries a few frequency-domain methods to identify cycles or intervals

Swimming-HR -- a post-lockdown file plotting heart-rate during interval swimming 

These are data files:


Data.zip -- the original JSON files from Fitbit, read by the JSON-to-DF notebook

PKL.zip -- the output of the JSON-to-DF notebook which is used as input by the other notebooks

Data was accessed via: https://www.fitbit.com/settings/data/export under 'Export Your Account Archive'
and through the Fitbit Web API for the Swimming-HR file

