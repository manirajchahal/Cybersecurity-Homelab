# Cybersecurity-Homelab

# Cybersecurity Homelab

## Description
I designed and built a comprehensive cybersecurity homelab to simulate real-world network security scenarios in a closed, controlled environment. This project allowed me to gain hands-on experience in configuring and integrating multiple security technologies, including firewall configuration, SIEM integration, and network segmentation.

## Table of Contents
- [Technologies](#technologies)
- [Highlights](#highlights)
- [Project Structure](#project-structure)
- [Setup & Configuration](#setup--configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Technologies
- **OPNsense Firewall:**  
  - Installed on an Intel-based PC.  
  - Configured as the central network defense system with custom firewall rules, NAT, and log forwarding.
- **SIEM Implementation (Wazuh on Raspberry Pi 5):**  
  - Deployed Wazuh on a Raspberry Pi 5 (16GB RAM) to collect, analyze, and visualize security logs for real-time threat detection and response.
- **Network Segmentation:**  
  - Utilized a Netgear 8-port Gigabit switch with VLAN configurations to segregate traffic and isolate critical network segments.

## Highlights
- Developed expertise in firewall configuration and advanced network security.
- Gained hands-on experience with SIEM integration, threat detection, log analysis, and incident response.
- Improved skills in network segmentation and troubleshooting hardware compatibility.
- Built a robust lab environment for safely experimenting with offensive and defensive cybersecurity techniques.

## Project Structure
The repository is organized into several directories:
- **docs/**: Contains documentation, such as network diagrams and detailed setup guides.
- **firewall/**: Includes OPNsense configuration backups and custom rules.
- **siem/**: Houses Wazuh configuration files and integration scripts.
- **network/**: Contains documentation and scripts related to network segmentation and VLAN configurations.

## Setup & Configuration
1. **OPNsense Firewall Setup:**
   - Install OPNsense on your Intel-based PC.
   - Import the configuration file provided in `firewall/OPNsense_config_backup.xml`.
   - Customize the firewall rules, NAT settings, and log forwarding as needed.

2. **Wazuh SIEM Setup on Raspberry Pi 5:**
   - Install the required operating system on your Raspberry Pi 5.
   - Follow the installation guide in `docs/setup_guide.md` to deploy Wazuh.
   - Use the configuration files in the `siem/wazuh_configurations/` folder to set up agents and manager rules.

3. **Network Segmentation:**
   - Configure your Netgear 8-port Gigabit switch according to the VLAN configuration documented in `network/vlan_configuration.md`.
   - Ensure critical network segments are properly isolated.

## Usage
- Use this homelab as a sandbox environment for testing cybersecurity tools and techniques.
- Experiment with modifying configurations, adding new security measures, and simulating attack scenarios.
- Refer to the documentation in the `docs/` folder for more detailed guides and troubleshooting tips.

## Contributing
Contributions, improvements, and suggestions are welcome! Please fork the repository and submit a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
