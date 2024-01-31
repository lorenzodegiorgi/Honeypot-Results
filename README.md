<!-- PROJECT LOGO -->
<br />
  <h3 align="center">Honeypot Results</h3>
</p>



<!-- TABLE OF CONTENTS -->

<details open="open">
  <summary><h2 style="display: inline-block">Table of 
Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->

## About The Project

Artifacts and configurations in this repo comes from an honeypot that I 
made up. Details about the honeypot can be found [here](https://lorenzodegiorgi.github.io/2024/01/09/Wazuh.html) \
The folders contains:
- agent_log: logs from webserver (access.log), from SSH honeypot (cowrie_log.zip) and from Suricata (eve.json).
- configurations: configuration of Wazuh Agent (ossec.conf) and cowrie 
(cowre.cfg.dist).
- P2PInfect: this folder contains the malware dropped into the honeypot, probably it's P2PInfect. Specifically *hhXx6VBudz.zip* contains the malware itself (please be careful! Do not unzip it if you do not know what are doing!). Folder contains also the strace output obtained by running it an a sandbox.
- Pcaps: the folder contains some relevant pcap file saved by Suricata. It's not the full export.
- Unknown_Malware: this folders contains bash script and tar dropped into the honeypot. They are potentially dangerous file, please do not unzip it if you do not know what you are doing.

<!-- GETTING STARTED -->

