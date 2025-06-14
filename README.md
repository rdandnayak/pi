- Cloudflared config stored at /etc/cloudflared/config.yml


# backup cloudflared config
tunnel: my-pi-tunnel
credentials-file: /home/rdandnayak/.cloudflared/948cf863-bb09-4161-82c5-cabcfca23b03.json

ingress:
  - hostname: vpn.dandnayak.shop
    service: http://localhost:80
  - service: http_status:404


# how i have setup rasberry pi
https://www.youtube.com/watch?v=oP6Zd5NFGnU


# how i have setup wireguard VPN
https://docs.pi-hole.net/guides/vpn/wireguard/client/
