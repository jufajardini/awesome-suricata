# Awesome Suricata [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) [![CC0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg?style=flat-square)](http://creativecommons.org/publicdomain/zero/1.0/)

> Awesome things somehow related to [Suricata IDS](https://suricata.io/).

Contributions are welcome, please feel free to send a PR!

## Contents

- [Input Tools](#input-tools)
- [Output Tools](#output-tools)
- [Operations, Monitoring and Troubleshooting](#operations-monitoring-and-troubleshooting)
- [Programming libraries and toolkits](#programming-libraries-and-toolkits)
- [Dashboards and Templates](#dashboards-and-templates)
- [Development Tools](#development-tools)
- [Documentation and Guides](#documentation-and-guides)
- [Analysis tools](#analysis-tools)
- [Rule sets](#rule-sets)
- [Rule/security content management and handling](#rulesecurity-content-management-and-handling)
- [Systems using Suricata](#systems-using-suricata)
- [Training](#training)
- [Simulation and Testing](#simulation-and-testing)
- [Data sets](#data-sets)
- [Misc](#misc)


## Input Tools

- [PacketStreamer](https://github.com/deepfence/PacketStreamer) - Distributed tcpdump for cloud native environments.


## Output Tools

- [suricata-kafka-output](https://github.com/Center-Sun/suricata-kafka-output) - Suricata Eve Kafka Output Plugin for Suricata 6.
- [suricata-redis-output](https://github.com/jasonish/suricata-redis-output) - Suricata Eve Redis Output Plugin for Suricata 7.
- [Meer](https://github.com/quadrantsec/meer) - Meer is a "spooler" for Suricata / Sagan.
- [FEVER](https://github.com/DCSO/fever) - Fast, extensible, versatile event router for Suricata's EVE-JSON format.
- [Suricata-Logstash-Templates](https://github.com/pevma/Suricata-Logstash-Templates) - Templates for Kibana/Logstash to use with Suricata IDPS.
- [Lilith](https://github.com/VVelox/Lilith) - Reads EVE files into SQL as well as search stored data.


## Operations, Monitoring and Troubleshooting

- [slinkwatch](https://github.com/DCSO/slinkwatch) - Automatic enumeration and maintenance of Suricata monitoring interfaces.
- [suri-stats](https://github.com/regit/suri-stats) - A tool to work on suricata `stats.log` file.
- [Mauerspecht](https://github.com/DCSO/mauerspecht) - Simple Probing Tool for Corporate Walled Garden Networks.
- [ansible-suricata](https://github.com/GitMirar/ansible-suricata) - Suricata Ansible role (slightly outdated).
- [MassDeploySuricata](https://github.com/pevma/MassDeploySuricata) - Mass deploy and update Suricata IDPS using Ansible IT automation platform.
- [docker-suricata](https://github.com/jasonish/docker-suricata) - Suricata Docker image.
- [Suricata-Monitoring](https://github.com/VVelox/Suricata-Monitoring) - LibreNMS JSON / Nagios monitor for Suricata stats.
- [Terraform Module for Suricata](https://github.com/onetwopunch/terraform-google-suricata) - Terraform module to setup Google Cloud packet mirroring and send packets to Suricata IDS.
- [InfluxDB Suricata Input Plugin](https://github.com/influxdata/telegraf/tree/master/plugins/inputs/suricata) - Input Plugin for Telegraf to collect and forward Suricata `stats` logs (included out of the box in recent Telegraf releases).
- [suricata_exporter](https://github.com/corelight/suricata_exporter) - Simple Prometheus exporter written in Go exporting stats metrics scraped from Suricata socket.

## Programming libraries and toolkits

- [rust-suricatax-rule-parser](https://github.com/jasonish/rust-suricatax-rule-parser) - Experimental Suricata Rule Parser in Rust.
- [go-suricata](https://github.com/ks2211/go-suricata) - Go Client for Suricata (Interacting via Socket).
- [gonids](https://github.com/google/gonids) - Go library to parse IDS rules for engines like Snort and Suricata.
- [surevego](https://github.com/rhaist/surevego) - Suricata EVE-JSON parser in Go.
- [suricataparser](https://github.com/m-chrome/py-suricataparser) - Pure python parser for Snort/Suricata rules.
- [py-idstools](https://github.com/jasonish/py-idstools) - Snort and Suricata Rule and Event Utilities in Python (Including a Rule Update Tool).


## Dashboards and Templates

- [KTS](https://github.com/StamusNetworks/KTS) - Kibana 4 Templates for Suricata IDPS Threat Hunting.
- [KTS5](https://github.com/StamusNetworks/KTS5) - Kibana 5 Templates for Suricata IDPS Threat Hunting.
- [KTS6](https://github.com/StamusNetworks/KTS6) - Kibana 6 Templates for Suricata IDPS Threat Hunting.
- [KTS7](https://github.com/StamusNetworks/KTS7) - Kibana 7 Templates for Suricata IDPS Threat Hunting.


## Development Tools

- [Suricata Language Server](https://github.com/StamusNetworks/suricata-language-server) - Suricata Language Server is an implementation of the Language Server Protocol for Suricata signatures. It adds syntax check, hints and auto-completion to your preferred editor once it is configured.
- [suricata-ls-vscode](https://github.com/StamusNetworks/suricata-ls-vscode) - Suricata IntelliSense Extension using the Suricata Language Server.
- [suricata-highlight-vscode](https://github.com/dgenzer/suricata-highlight-vscode) - Suricata Rules Support for Visual Studio Code (syntax highlighting, etc).
- [SublimeSuricata](https://github.com/regit/SublimeSuricata) - Basic Suricata syntax highlighter for Sublime Text 3.


## Documentation and Guides

- [SEPTun](https://github.com/pevma/SEPTun) - Suricata Extreme Performance Tuning guide.
- [SEPTun-Mark-II](https://github.com/pevma/SEPTun-Mark-II) - Suricata Extreme Performance Tuning guide - Mark II.
- [suricata-4-analysts](https://github.com/StamusNetworks/suricata-4-analysts) - The Security Analyst's Guide to Suricata.


## Analysis tools

- [Suricata Analytics](https://github.com/StamusNetworks/suricata-analytics) - Various resources that are useful when interacting with Suricata data.
- [Malcolm](https://github.com/cisagov/Malcolm) - A powerful, easily deployable network traffic analysis tool suite for full packet capture artifacts (PCAP files), Zeek logs and Suricata alerts.
- [Evebox](https://github.com/jasonish/evebox) - Web Based Event Viewer (GUI) for Suricata EVE Events in Elastic Search.


## Rule sets

- [nids-rule-library](https://github.com/klingerko/nids-rule-library#readme) - Collection of various open-source and commercial rulesets.
- [Stamus Lateral Movement Detection Rules](https://ti.stamus-networks.io/open/stamus-lateral-rules.tar.gz) - Suricata ruleset to detect lateral movement.
- [QuadrantSec Suricata Rules](https://github.com/quadrantsec/suricata-rules) - QuadrantSec Suricata rules.
- [Cluster25/detection](https://github.com/Cluster25/detection) - Cluster25's detection rules.
- Networkforensic.dk (NF) rules sets: 
  - [NF IDS rules](https://networkforensic.dk/SNORT/NF-local.zip)
  - [NF SCADA IDS Rules](https://networkforensic.dk/SNORT/NF-SCADA.zip)
  - [NF Scanners IDS Rules](https://networkforensic.dk/SNORT/NF-Scanners.zip)


## Rule/security content management and handling

- [sidallocation.org](https://sidallocation.org/) - Sid Allocation working group, list of SID ranges.
- [Scirius](https://github.com/StamusNetworks/scirius) - Web application for Suricata ruleset management and threat hunting.
- [IOCmite](https://github.com/sebdraven/IOCmite) - Tool to create dataset for suricata with indicators of MISP instances and add sightings in MISP if an indicator of dataset generates an alert.
- [luaevilbit](https://github.com/regit/luaevilbit) - An Evil bit implementation in luajit for Suricata.
- [Lawmaker](https://www.3coresec.com/lawmaker) - Suricata IDS rule management system.
- [surify-cli](https://github.com/dgenzer/surify-cli) - Generate suricata-rules from collection of IOCs (JSON, CSV or flags) based on your suricata template.
- [suricata-prettifier](https://github.com/theY4Kman/suricata-prettifier) - Command-line tool to format and syntax highlight Suricata rules.
- [OTX-Suricata](https://github.com/AlienVault-OTX/OTX-Suricata) - Create rules and configuration for Suricata to alert on indicators from an OTX account.


## Systems using Suricata

- [SELKS](https://github.com/StamusNetworks/SELKS) - A Suricata based IDS/IPS/NSM distro.
- [Amsterdam](https://github.com/StamusNetworks/Amsterdam) - Docker based Suricata, Elasticsearch, Logstash, Kibana, Scirius aka SELKS.


## Training

- [Experimental Suricata Training Environment](https://github.com/jasonish/experimental-suricata-training) - Experimental Suricata Training Environment.


## Simulation and Testing

- [Leonidas](https://github.com/WithSecureLabs/leonidas) - Automated Attack Simulation in the Cloud, complete with detection use cases.
- [speeve](https://github.com/satta/speeve) - Fast, probabilistic EVE-JSON generator for testing and benchmarking of EVE-consuming applications.
- [Dalton](https://github.com/secureworks/dalton) - Suricata and Snort IDS rule and pcap testing system.


## Data sets

- [suricata-sample-data](https://github.com/FrankHassanabad/suricata-sample-data) - Repository of creating different example suricata data sets.


## Misc

- [Suriwire](https://github.com/regit/suriwire) - Wireshark plugin to display Suricata analysis info.
- [bash_cata](https://github.com/isMTv/bash_cata) - A simple script that processes the generated Suricata eve-log in real time and, based on alerts, adds an ip-address to the MikroTik Address Lists for a specified time for subsequent blocking.
- [suriGUI](https://github.com/control-owl/suriGUI) - GUI for Suricata + Qubes OS.
