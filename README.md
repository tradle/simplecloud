# Premise

1. Linux evolved in the last 5-10 years to let us create a beautful and powerful Cloud, without significant investments made by Megascalers (AWS, Azure and GCP).

1. Despite the dominance of Megascaler / Hyperscalers, Cloud industry is surging with new entrants like Fly.io and wuth the signifant evolution among the existing ones, like Cloudflare, Fastly.com.

1. There is one area that Hyperscalers are not addressing today, a **Personal Cloud**. 
This segment of the market does not exist today, closest to it being the VPS. VPS business existed since 1990s but its target audience was always the techically savvy. Personal Cloud is for the mass consumer.

# Goals of Personal Cloud
1. People became a product of Facebook, Google and other SaaS app providers. Our goal is to restore the Internet to the conditions when apps do not own us and our data. 
2. We are live in a increasingly multi-device world, with mobile, tablets, PCs, vehicle and home automation computing devices coming online at a rapid pace. We need a personal operating system to manage those devices, put them on one virtual secure network, while logging into it from many places, to exchange data securely between our devices and to run AI and classic algorithms on them, adjusting well to the capabilities. Cloud is one of such devices, with specific capabilities that enahnce operations of other personal devices. Cloud 

# Components of the Personal Cloud
3 major components: network, compute and data virtualization

## Network

We use Wireguard, the latest network encryption and virtualization technology, which allows us to offer you:

- Secure line on public Wifi and even at home? - warp
    - wireguard on LAN
- No snooping of browsing history by ISP - warp
- Service mesh: VLAN for Airdrop and P2P apps
    - why do u need one? - no warp
    - maybe just VLAN, and not even VPN? 
    - teams 
- Firewall
- IPv6 vs IPv4

### Premium features

- **No snooping by websites**. By default, the websites you viti will see the same IP address that they would see when you are not using our solution. We offer an option for you to come to them with a different temporary IP address. Gives you that extra protection.
- **Block ads in apps and browser**. Add do a full surveilance on us. This option will blocs many of the ads for all of your devices, without you needeing to do anything. No more installing browser extensions, ad blockers, etc. We feel bad about advertisement supported services, but perhaps their time is over. Personal Cloud offers alternative apps that never take your data.
- **Pay with cryptocurrnecy** to avoid giving us your name and card when signing up.

### Not supported
This solution is built of privacy. If you're doing it to mask potentially illegal activity, don't - you will get in trouble. This may include:

- Torrenting of movies and other copyrighted materials
- Geolocation switching to watch Netflix shows which are not available in your home country

It is also important to understand the limitations on our ability to protect your privacy:

- **Defence from us**. We do not have an ability to access your data, secret keys or network activity. But as we accept payments from you, we may know who you are, if you use the credit card payment mechanism. If you do not want that, pay us please with cryptocurrency if your jurisdiction allows it.
- **Defence from the landlord**. With this solution the capability of the Data Center to know what your are doing is significantly reduces. What remains is:
    - data center will have an ability to take the operating memory snapshot of your personal virtual machine and try to deduce some information from it. Note that all cloud providers have this capability. Yet, the solution for this is coming - encrypted memory for virtual machines will be possible in about a year. Note that this relates only to data in RAM, while the data kept in storage are always encrypted.
    - your home router or your mobile on a cell phone network will reveal their network IP address to the Data Center's network. This is standard with the IP protocol used by the Internet. This does not reveal any transmitted data, just the source IP address (e.g. router) and the destination IP which is the address of your virtual machine. You can't hide the destination, but if you want to hide your source IP address, your need to look for Tor or other similar solutions. 
- **Government agency** may compel the Data Center to perform the above actions, using the due process or covertly.


