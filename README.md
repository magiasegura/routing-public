# IDTBX Routing

Auto-updated routing rule-sets for VPN clients. Rebuilt every 4 hours.

Base rule-set content is sourced from [DigneZzZ/routing](https://github.com/DigneZzZ/routing) and merged with your own additions in [`custom.yaml`](custom.yaml), then self-compiled into `.list` / `.mrs` / `geosite.dat` / `geoip.dat`. To add sites, edit `custom.yaml` (one domain/CIDR list per category) — nothing else.

<details>
<summary>Rule-sets (text)</summary>

| List | Link |
|---|---|
| proxy | [proxy.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/proxy.list) |
| direct | [direct.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/direct.list) |
| reject | [reject.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/reject.list) |
| youtube | [youtube.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/youtube.list) |
| ai | [ai.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/ai.list) |
| games | [games.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/games.list) |
| ip-check | [ip-check.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/ip-check.list) |
| vpndetect | [vpndetect.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/vpndetect.list) |
| proxy-ip | [proxy-ip.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/proxy-ip.list) |
| direct-ip | [direct-ip.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/direct-ip.list) |
| refilter-domain | [refilter-domain.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/refilter-domain.list) |
| refilter-domain-full | [refilter-domain-full.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/refilter-domain-full.list) |
| refilter-ip | [refilter-ip.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/refilter-ip.list) |
| refilter-ip-full | [refilter-ip-full.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/refilter-ip-full.list) |
| refilter-community | [refilter-community.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/refilter-community.list) |
| proxy-ip-full | [proxy-ip-full.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/proxy-ip-full.list) |
| ru-ip | [ru-ip.list](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/ru-ip.list) |
| proc-games | [proc-games.yaml](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/proc-games.yaml) |
| proc-torrent | [proc-torrent.yaml](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/proc-torrent.yaml) |
| proc-ru | [proc-ru.yaml](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/proc-ru.yaml) |

</details>

<details>
<summary>Rule-sets (mrs)</summary>

| List | Link |
|---|---|
| proxy | [proxy.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/proxy.mrs) |
| direct | [direct.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/direct.mrs) |
| reject | [reject.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/reject.mrs) |
| youtube | [youtube.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/youtube.mrs) |
| ai | [ai.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/ai.mrs) |
| games | [games.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/games.mrs) |
| ip-check | [ip-check.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/ip-check.mrs) |
| vpndetect | [vpndetect.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/vpndetect.mrs) |
| proxy-ip | [proxy-ip.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/proxy-ip.mrs) |
| direct-ip | [direct-ip.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/direct-ip.mrs) |
| refilter-domain | [refilter-domain.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/refilter-domain.mrs) |
| refilter-domain-full | [refilter-domain-full.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/refilter-domain-full.mrs) |
| refilter-ip | [refilter-ip.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/refilter-ip.mrs) |
| refilter-ip-full | [refilter-ip-full.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/refilter-ip-full.mrs) |
| refilter-community | [refilter-community.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/refilter-community.mrs) |
| proxy-ip-full | [proxy-ip-full.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/proxy-ip-full.mrs) |
| ru-ip | [ru-ip.mrs](https://raw.githubusercontent.com/magiasegura/routing-public/main/release/ru-ip.mrs) |

</details>

<details>
<summary>Xray geo-data</summary>

| File | Link |
|---|---|
| geosite.dat (full) | [geosite.dat](https://raw.githubusercontent.com/magiasegura/routing-public/main/xray/geosite.dat) |
| geoip.dat (full) | [geoip.dat](https://raw.githubusercontent.com/magiasegura/routing-public/main/xray/geoip.dat) |
| geosite.dat (lite) | [happ/geosite.dat](https://raw.githubusercontent.com/magiasegura/routing-public/main/xray/happ/geosite.dat) |
| geoip.dat (lite) | [happ/geoip.dat](https://raw.githubusercontent.com/magiasegura/routing-public/main/xray/happ/geoip.dat) |

</details>

<details>
<summary>Templates</summary>

MihoMo (Clash.Meta) templates based on [DigneZzZ/routing](https://github.com/DigneZzZ/routing), repointed to this CDN (so they use the custom-merged rule-sets):

| Template | Variant | Link |
|---|---|---|
| MihoMo (desktop, full) | PC + RKN registry | [template.yaml](https://raw.githubusercontent.com/magiasegura/routing-public/main/template.yaml) |
| MihoMo (desktop, lite) | PC, lightweight | [template-lite.yaml](https://raw.githubusercontent.com/magiasegura/routing-public/main/template-lite.yaml) |
| MihoMo (mobile, lite) | phone, iOS-friendly | [template-mobile.yaml](https://raw.githubusercontent.com/magiasegura/routing-public/main/template-mobile.yaml) |
| MihoMo (mobile, full) | phone + RKN registry | [template-mobile-full.yaml](https://raw.githubusercontent.com/magiasegura/routing-public/main/template-mobile-full.yaml) |
| MihoMo (xkeen/Keenetic) | custom (not from DigneZzZ) | [template-xkeen.yaml](https://raw.githubusercontent.com/magiasegura/routing-public/main/template-xkeen.yaml) |

</details>

<details>
<summary>Client configs</summary>

| Config | JSON | Link |
|---|---|---|
| Happ (lite) | [default.json](https://raw.githubusercontent.com/magiasegura/routing-public/main/xray/happ/default.json) | [deeplink](xray/happ/default_deeplink.txt) |
| Happ (full) | [full.json](https://raw.githubusercontent.com/magiasegura/routing-public/main/xray/happ/full.json) | [deeplink](xray/happ/full_deeplink.txt) |
| INCY (lite) | [default.json](https://raw.githubusercontent.com/magiasegura/routing-public/main/xray/incy/default.json) | [deeplink](xray/incy/default_deeplink.txt) |
| INCY (full) | [full.json](https://raw.githubusercontent.com/magiasegura/routing-public/main/xray/incy/full.json) | [deeplink](xray/incy/full_deeplink.txt) |
| V2RayTUN | [routing.json](https://raw.githubusercontent.com/magiasegura/routing-public/main/xray/v2raytun/routing.json) | [deeplink](xray/v2raytun/routing_deeplink.txt) |

</details>

<details>
<summary>Deeplinks</summary>

| | Happ | INCY |
|---|---|---|
| **Lite** (iOS) | [deeplink](xray/happ/default_deeplink.txt) | [deeplink](xray/incy/default_deeplink.txt) |
| **Full** (Android/PC) | [deeplink](xray/happ/full_deeplink.txt) | [deeplink](xray/incy/full_deeplink.txt) |

| V2RayTUN |
|---|
| [deeplink](xray/v2raytun/routing_deeplink.txt) |

</details>
