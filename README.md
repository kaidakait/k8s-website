# k8s-website
The website that is hosted by my homelab

Homelab items

1. list of hardware & software
2. Internet guides & references
------------------------------------------------------------------------------------------------------------------------
HARDWARE:
* Power and UPS Batteries:
  - 1 x Cyberpower CP1300EPFCLCD-UK Backup UPS PFC Pure Sinewave 1300VA/780W 2 x UK Sockets 4 x IEC
  - 2 x CyberPower BR1200ELCD-UK BRICs Series, 1200VA/720W, 6 UK Outlets 
  - 2 x ZOUD Security Standby Power Supply Multifunctional 5V/2A UPS Power Bank 

* Networking:
  - 3 x Cisco SG350-10 10-Port Gigabit Managed Switch (SG350-10-K9-UK), Black
  - 1 x Linksys E4200 router - rooted to DDWRT
  - 2 x TP-Link AC750 Dual Band Wi-Fi Travel Router
  - 2 x TP-Link Managed PoE Network Switch 5-Port Gigabit, 4 PoE+ ports
  - 1 x ZTE MF833U1, CAT4/4G USB Dongle - GiffGaff sim
  - 1 x BTHomehub - Smart Hub 2
  - 2 x TP-Link TL-PA9020PKIT 2-Port Gigabit Passthrough Powerline
  - 1 x TP-Link TL-PA7017P KIT 1-Port Gigabit Passthrough Powerline
  - 1 x pair 10/100M 1 BNC to rj45 Port IP Extender CCTV HD IP Video Extender EOC slave Ethernet over Coax Extender up to 2KM
    ** Various CAT5e & CAT6 cables

* Server/hosts/PC's:
  - 5 x Sharevdi Fanless Mini PC Intel Celeron N2940 Quad-core,4x Intel Gigabit Ethernet, 8G RAM 128G SSD/USB 3.0/2.4G WiFi/HDMI/VGA
  - 1 x Dell OptiPlex 755 with added PCI & PCIe cards
  - 1 x Dell Lattituded E6320

* Storage:
  - 1 x Synology DS218j 2 Bay Desktop NAS
  - 1 x Yottamaster 5 Bay Hard Drive Enclosure,Aluminum USB3.0 External HDD Enclosure for 2.5"/3.5" SATA HDD/SSD, 5X16TB Hard Drive Caddy with 80mm Fan
  - 1 x Sabrent USB 3.0 4 Bay 2.5" Hard drive/SSD Docking Station with Fan
    ** Various SATA rotating Disks and various SSD's (old and used disks from other systems)

----------------------------------------
SOFTWARE:
- Proxmox - pve-manager/7.0-8/b1dbf562 (running kernel: 5.11.22-1-pve) - evaluation version - on the PVE hosts
- Cisco switch IOS Version: 2.3.5.63 - on the cisco switches
- Ubuntu 21.04 hirsuite - on the k8's nodes
    Kubernetes - v1.23.3 - containerd 1.5.5
- VyOS 1.3-rolling-202012231522 equuleus - on one of the Sharevdi Fanless Mini PC's
- Synology DSM 7.0.1-42218
- DDRWT Firmware: DD-WRT v3.0-r30880 mega (11/14/16)
- ZFS - zfs/kmod-2.0.4 - on the promox hosts
- Glusterfs - glusterfs 10.0 - on the promox hosts
--   SOFTWARE on VMs and containers on the Proxmox hosts:
  -     Kubernetes Master node - v1.23.3 - containerd 1.5.5
  -     Haproxy 2.4.0
  -     Heketi-cli  & Glusterfs 10.0
  -     DNSMASQ  2.80
  -     ZoneMinder 1.34
--  SOFTWARE on Kubernetes v1.23.3 - containerd 1.5.5
   -    Nginx:latest
        * will be attempting to containerise other apps
      -     zoneminder
      -     Grafana/Kibana
      -     Nagios
      -     Homeassistant
      -     Nextcloud
      -     Rancid
      -     Plex
      -     Freenas

* for video editing KDENLIVE

* BACKGROUND MUSIC FOR VIDEOS

1.  Lo-Fi Lounge Chill Hip Hop CITY by Alex-Productions | https://www.youtube.com/channel/UCx0_M61F81Nfb-BRXE-SeVA
    Music promoted by https://www.chosic.com/free-music/all/
    Creative Commons CC BY 3.0
    https://creativecommons.org/licenses/by/3.0/


2.  Affirmations by Scott Buckley | www.scottbuckley.com.au
    Music promoted by https://www.chosic.com/free-music/all/
    Creative Commons Attribution 4.0 International (CC BY 4.0)
    https://creativecommons.org/licenses/by/4.0/

** Music between networking layers created and produced by Kaidi-t

------------------------------------------------------------------------------------------------------------------------
* INTERNET GUIDES AND REFERENCES:

   - Linux - on the job learning [Canonical]
          - https://Udemy.com 
          - https://linuxfoundation.org 
          - https://acloudguru.com 

  - Proxmox - self learning & youtube.com [LearnLinuxTV] - https://www.youtube.com/channel/UCxQKHvKbmSzGMvUrVtJYnUA

  - Cisco switches - CCNA & on the job learning

  - VYOS - youtube.com & https://docs.vyos.io/

  - DDRWT - youtube.com & https://forum.dd-wrt.com/

  - ZFS - on the job learning & https://docs.oracle.com/cd/E19253-01/819-5461/index.html

  - Glusterfs - on the job learning & https://docs.gluster.org/
              - https://www.jamescoyle.net/how-to/471-zfs-and-glusterfs-network-storage  

  - Kubernetes & Heketi-cli
           - On the job learning
           - https://kubernetes.io/ 
           - https://www.youtube.com/c/wenkatn-justmeandopensource
           - https://github.com/justmeandopensource
           - https://Udemy.com 
           - https://linuxfoundation.org 
           - https://acloudguru.com 

  - Ansible - on the job learning
        - https://youtube.com
        - https://Udemy.com 
        - https://acloudguru.com 

  - Python & Golang - on the job learning
                - https://udacity.com
                - https://youtube.com
                - https://Udemy.com 
                - https://linuxfoundation.org 
                - https://acloudguru.com 

  - Github  - on the job learning
        - https://youtube.com
