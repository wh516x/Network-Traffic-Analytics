# Network-Traffic-Analytics
Network Traffic Analytics Implementation with ODL


The main target is to integrate ODL machine into PNDA machine to test the capabilities of PNDA Analytics Engine. We use GNS3 to create network topology and use this data for PNDA Analytics using openflow1.3 protocol.
The requirements to integrate OpenDaylight with PNDA
1.	Pick a data source, i.e. an OpenDaylight application that can supply data to an OpenDaylight event topic.
2.	Configure the OpenDaylight event aggregator to collect the desired data and publish it on a topic.
3.	Deploy the OpenDaylight Kafka Plugin and configure it to forward events to the Kafka message bus of your PNDA instance.


Document shows the errors encountered while Implemente Machine Learning with ODL
https://wh516x.medium.com/pnda-install-issue-845dee81372c
