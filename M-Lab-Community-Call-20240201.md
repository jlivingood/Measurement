# Preliminary Thoughts for M-Lab Community Call on 02 Feb 2024

## Opening Question
> Access to high speed Internet does not necessarily mean access to high quality Internet. But if not speed then what? How should we measure Internet quality?
> Over the past decade, network and Internet measurement experts have been reaching a consensus that throughput measurements, more commonly referred to as “speed” tests, are not the only suitable proxy for the quality of an user’s experience using the Internet and that other metrics such as unloaded and loaded latency, jitter, and packet loss should also be considered. Additionally, experts often discuss the need for measurements that account for the impact of local wi-fi networks, as well as metadata to differentiate between different types of access technologies such as fiber and DSL. 

## Questions Posed
> What datasets, tools and methodologies should be included?

Approaching the discussion this way is problematic. Rather than starting with existing datasets and tools and trying for force fit them to a particular question, start first with the questions to which the community wants answers. Then use that to guide you to appropriate datasets and tools - those that are fit to purpose. 

Some example questions:
1. Broadband Capacity - Per User
2. Broadband Capacity - Per ISP Tier or ISP
3. Broadband Capacity - Specific Geograpghic Area
4. Broadband Responsiveness (Working Latency & Jitter) - Per User
5. Broadband Responsiveness (Working Latency & Jitter) - Per ISP Tier or ISP
6. Broadband Responsiveness (Working Latency & Jitter) - Specific Geographic Area
7. Troubleshooting Connection Impairment - Per User
8. Detecting Route Impairment & Route Loss
9. Detecting Outages - Per ISP
10. Detecting Outages - Specific Geographic Area
11. Validating App-Agnosting Network Management Practices / Detecting App-Specific Practices (through error or policy)
12. Discovery of Access Network Attributes (access type, tier configuration, ISP, device type, device or firmware version/age, etc.)
13. Discovery of User LAN Attributes (network types, device types, operarting system versions, device age, etc.)
14. Interconnection Capacity - Per ISP
15. Interconnection Capacity - Per ISP-Destination Network Combination
16. Encrypted Traffic Volume & Share - Per ISP
17. Encrypted Traffic Volume & Share - Specific Geographic Area
18. Traffic Volume Over Time - Per ISP
19. Traffic Volume Over Time - Specific Geographic Area
20. Traffic Volume Spikes - Key Contributors (events, destintions, etc.)
21. RPKI Support - Per ISP
22. Routing Security - Other Metrics (ROAs, SAV, etc.)
23. DNS Security Support - Per ISP (DNSSEC validation, DNS Over HTTPS support, DNS Over TLS support, etc.)
24. Carrier Grade NAT Detection - Per ISP (e.g. native dual stack vs. CGN to support IPv4)
    Destination Concentration (Centralization) - Specific Geographic Area (e.g., how concentrated is destination traffic in the US)
25. ??


> What organizations, consortiums and experts should be consulted?

1. ISPs
2. App Developers (to describe what their current & future QoE needs are)
3. Measurement Platform/Test Developers
4. Measurement Researchers
5. Policymakers/Regulators & Other Governement Orgs (e.g., grant makers, subsidy distributors)
6. End Users

> What conversations (e.g., newsletters, mailing lists etc.) should we be part of?

It may be worth tracking the work of the Internet Research Task Force's (IRTF) Measurement and Analysis for Protocols (MAPRG) research group (https://datatracker.ietf.org/rg/maprg/about/), as well as the Internet Engineering Task Force's (IETF) IP Performance Measurement (https://datatracker.ietf.org/wg/ippm/about/) working group. 

I believe the Broadband Internet Technical Advisory Group (BITAG, https://bitag.org/) is also considering a brief paper on broadband measurement. 
 
> If you are interested in helping shape this work, how are you interested in contributing? Through an advisory committee? Through a survey? A workshop? Other formats?

This effort should rely on primarily asynchronous tools for collaboration. The need for async comms can be met via email and async document collaboration can be met via GitHub. The effort will likely also benefit from periodic syncronous meetings to debate topics, reach consensus, assign work items, and agree on deadlines. This can be met via periodic video conferences. It may be beneficial to kick off the effort with a higher context face-to-face workshop, which can better support more detailed strategic discussion and planning. 

## Community Call Info
https://www.measurementlab.net/blog/feb24-community-call/
