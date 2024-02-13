# survey-scanner
This repository publishes the sources of Internet-Wide Scans. 

The list was created from [NICTER darknet monitoring](https://www.nicter.jp/en). We have examined source IP addresses of the packets observed at NICTER and identified the survey-scan organization and their IP addresses by reverse DNS lookups, WHOIS searches, and HTTP(S) accesses to the scanner’s IP addresses. We also searched for relevant descriptions on the official website of each survey-scanner. The detailed process can be found at [NICTER report 2023](https://csl.nict.go.jp/report/NICTER_report_2023.pdf).

## survey-scanners' list
We have identified 79 survey-scan organizations in 2023. The following file contains the list of name, type, TCP port counts, UDP port counts, observed days in 2023 and a reference URL of each survey-scan organization. The list is sorted in descending order of the number of packets observed in 2023.

```
scanorg_2023.csv
```

## survey-scanners' IP addresses
We have identified 11,186 IP addresses of survey-scanners. Following JSON file contains the list of IP address, name of the survey-scan organization and the last date when we observed a scan packet from the IP address in 2023.

```
surveyscanner_2023.json
```
