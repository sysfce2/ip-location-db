# ip-location-db

This project provides IP to location databases in CSV and MMDB formats.

## Available database downloads

There are 3 types of IP database in this repository: `country`, `asn` and `city` files. All have their own 
standard format. Please use the provided CDN links rather than directly linking to files in this repository.

### Country

These files map IP ranges to country codes:

| Database | Type | Licence | Updated | IPv4 | IPv6 | IPv4-num | IPv6-num |
|---|---|---|---|---|---|---|---|
| ASN <br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/asn-country?color=success&style=flat-square&label=CSV)](https://www.npmjs.com/package/@ip-location-db/asn-country)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/asn-country-mmdb?color=success&style=flat-square&label=MMDB)](https://www.npmjs.com/package/@ip-location-db/asn-country-mmdb) | [Country](COUNTRY.md)| [CC0](https://creativecommons.org/publicdomain/zero/1.0/deed) | Daily | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/asn-country/asn-country-ipv4.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/asn-country-mmdb/asn-country-ipv4.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/asn-country/asn-country-ipv6.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/asn-country-mmdb/asn-country-ipv6.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/asn-country/asn-country-ipv4-num.csv) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/asn-country/asn-country-ipv6-num.csv) |
| GeoFeed + ASN<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/geo-asn-country?color=success&style=flat-square&label=CSV)](https://www.npmjs.com/package/@ip-location-db/geo-asn-country)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/geo-asn-country-mmdb?color=success&style=flat-square&label=MMDB)](https://www.npmjs.com/package/@ip-location-db/geo-asn-country-mmdb) | [Country](COUNTRY.md)| [CC0](https://creativecommons.org/publicdomain/zero/1.0/deed) | Daily | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/geo-asn-country/geo-asn-country-ipv4.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/geo-asn-country-mmdb/geo-asn-country-ipv4.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/geo-asn-country/geo-asn-country-ipv6.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/geo-asn-country-mmdb/geo-asn-country-ipv6.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/geo-asn-country/geo-asn-country-ipv4-num.csv) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/geo-asn-country/geo-asn-country-ipv6-num.csv) |
| GeoFeed + Whois + ASN<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/geo-whois-asn-country?color=success&style=flat-square&label=CSV)](https://www.npmjs.com/package/@ip-location-db/geo-whois-asn-country)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/geo-whois-asn-country-mmdb?color=success&style=flat-square&label=MMDB)](https://www.npmjs.com/package/@ip-location-db/geo-whois-asn-country-mmdb) | [Country](COUNTRY.md)| [CC0](https://creativecommons.org/publicdomain/zero/1.0/deed) | Daily | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/geo-whois-asn-country/geo-whois-asn-country-ipv4.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/geo-whois-asn-country-mmdb/geo-whois-asn-country-ipv4.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/geo-whois-asn-country/geo-whois-asn-country-ipv6.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/geo-whois-asn-country-mmdb/geo-whois-asn-country-ipv6.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/geo-whois-asn-country/geo-whois-asn-country-ipv4-num.csv) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/geo-whois-asn-country/geo-whois-asn-country-ipv6-num.csv) |
| [IPtoASN](https://iptoasn.com/)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/iptoasn-country?color=success&style=flat-square&label=CSV)](https://www.npmjs.com/package/@ip-location-db/iptoasn-country)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/iptoasn-country-mmdb?color=success&style=flat-square&label=MMDB)](https://www.npmjs.com/package/@ip-location-db/iptoasn-country-mmdb) | [Country](COUNTRY.md)| [PDDL](https://opendatacommons.org/licenses/pddl/1.0/) by [IPtoASN](https://iptoasn.com/) | Daily | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/iptoasn-country/iptoasn-country-ipv4.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/iptoasn-country-mmdb/iptoasn-country-ipv4.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/iptoasn-country/iptoasn-country-ipv6.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/iptoasn-country-mmdb/iptoasn-country-ipv6.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/iptoasn-country/iptoasn-country-ipv4-num.csv) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/iptoasn-country/iptoasn-country-ipv6-num.csv) |<!-- | [Webnet77](http://software77.net/geo-ip/)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/webnet77-country?color=success&style=flat-square&label=CSV)](https://www.npmjs.com/package/@ip-location-db/webnet77-country)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/webnet77-country-mmdb?color=success&style=flat-square&label=MMDB)](https://www.npmjs.com/package/@ip-location-db/webnet77-country-mmdb) | [Country](COUNTRY.md)| [Donationware](http://en.wikipedia.org/wiki/Donationware) by [Webnet77](http://software77.net/geo-ip/) | Daily | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/webnet77-country/webnet77-country-ipv4.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/webnet77-country-mmdb/webnet77-country-ipv4.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/webnet77-country/webnet77-country-ipv6.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/webnet77-country-mmdb/webnet77-country-ipv6.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/webnet77-country/webnet77-country-ipv4-num.csv)) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/webnet77-country/webnet77-country-ipv6-num.csv) | -->
| [DB-IP](https://db-ip.com/) Lite<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/dbip-country?color=success&style=flat-square&label=CSV)](https://www.npmjs.com/package/@ip-location-db/dbip-country)| [Country](COUNTRY.md)| [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) <br> by [DB-IP](https://db-ip.com/) | Monthly | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-country/dbip-country-ipv4.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-country-mmdb/dbip-country-ipv4.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-country/dbip-country-ipv6.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-country-mmdb/dbip-country-ipv6.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-country/dbip-country-ipv4-num.csv) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-country/dbip-country-ipv6-num.csv) |
| [GeoLite2](https://dev.maxmind.com/geoip/geoip2/geolite2/)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/geolite2-country?color=success&style=flat-square&label=CSV)](https://www.npmjs.com/package/@ip-location-db/geolite2-country)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/geolite2-country-mmdb?color=success&style=flat-square&label=MMDB)](https://www.npmjs.com/package/@ip-location-db/geolite2-country-mmdb) | [Country](COUNTRY.md)| GeoLite2 License by [MaxMind](https://www.maxmind.com/) | Twice weekly | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-country/geolite2-country-ipv4.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-country-mmdb/geolite2-country-ipv4.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-country/geolite2-country-ipv6.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-country-mmdb/geolite2-country-ipv6.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-country/geolite2-country-ipv4-num.csv) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-country/geolite2-country-ipv6-num.csv) |

### ASN

These files map IP ranges to [Autonomous System Number](https://en.wikipedia.org/wiki/Autonomous_system_%28Internet%29) details:

| Database | Type | Licence | Updated | IPv4 | IPv6 | IPv4-num | IPv6-num |
|---|---|---|---|---|---|---|---|
| [RouteViews](https://www.routeviews.org/routeviews/) + ASN + [DB-IP](https://db-ip.com/)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/asn?color=success&style=flat-square&label=CSV)](https://www.npmjs.com/package/@ip-location-db/asn)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/asn-mmdb?color=success&style=flat-square&label=MMDB)](https://www.npmjs.com/package/@ip-location-db/asn-mmdb) | [ASN](ASN.md) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) by [RouteViews](https://www.routeviews.org/routeviews/) and [DB-IP](https://db-ip.com/) | Daily | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/asn/asn-ipv4.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/asn-mmdb/asn-ipv4.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/asn/asn-ipv6.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/asn-mmdb/asn-ipv6.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/asn/asn-ipv4-num.csv) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/asn/asn-ipv6-num.csv) |
| [IPtoASN](https://iptoasn.com/)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/iptoasn-asn?color=success&style=flat-square&label=CSV)](https://www.npmjs.com/package/@ip-location-db/iptoasn-asn)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/iptoasn-asn-mmdb?color=success&style=flat-square&label=MMDB)](https://www.npmjs.com/package/@ip-location-db/iptoasn-asn-mmdb) | [ASN](ASN.md) | [PDDL](https://opendatacommons.org/licenses/pddl/1.0/) by [IPtoASN](https://iptoasn.com/) | Daily | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/iptoasn-asn/iptoasn-asn-ipv4.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/iptoasn-asn-mmdb/iptoasn-asn-ipv4.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/iptoasn-asn/iptoasn-asn-ipv6.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/iptoasn-asn-mmdb/iptoasn-asn-ipv6.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/iptoasn-asn/iptoasn-asn-ipv4-num.csv) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/iptoasn-asn/iptoasn-asn-ipv6-num.csv) |
| [DB-IP](https://db-ip.com/) Lite<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/dbip-asn?color=success&style=flat-square&label=CSV)](https://www.npmjs.com/package/@ip-location-db/dbip-asn)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/dbip-asn-mmdb?color=success&style=flat-square&label=MMDB)](https://www.npmjs.com/package/@ip-location-db/dbip-asn-mmdb) | [ASN](ASN.md) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)<br> by [DB-IP](https://db-ip.com/) | Monthly | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-asn/dbip-asn-ipv4.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-asn-mmdb/dbip-asn-ipv4.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-asn/dbip-asn-ipv6.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-asn-mmdb/dbip-asn-ipv6.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-asn/dbip-asn-ipv4-num.csv) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-asn/dbip-asn-ipv6-num.csv) |
| [GeoLite2](https://dev.maxmind.com/geoip/geoip2/geolite2/)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/geolite2-asn?color=success&style=flat-square&label=CSV)](https://www.npmjs.com/package/@ip-location-db/geolite2-asn)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/geolite2-asn-mmdb?color=success&style=flat-square&label=MMDB)](https://www.npmjs.com/package/@ip-location-db/geolite2-asn-mmdb) | [ASN](ASN.md) | GeoLite2 License by [MaxMind](https://www.maxmind.com/) | Twice weekly | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-asn/geolite2-asn-ipv4.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-asn-mmdb/geolite2-asn-ipv4.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-asn/geolite2-asn-ipv6.csv)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-asn-mmdb/geolite2-asn-ipv6.mmdb) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-asn/geolite2-asn-ipv4-num.csv) | [CSV](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-asn/geolite2-asn-ipv6-num.csv) |

### City

These files map IP ranges to more fine-grained location information:

| Database | Type | Licence | Updated | IPv4 | IPv6 | IPv4-num | IPv6-num |
|---|---|---|---|---|---|---|---|
| [DB-IP](https://db-ip.com/) Lite<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/dbip-city?color=success&style=flat-square&label=GZ)](https://www.npmjs.com/package/@ip-location-db/dbip-city)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/dbip-city-7z?color=success&style=flat-square&label=7z)](https://www.npmjs.com/package/@ip-location-db/dbip-city-7z)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/dbip-city-mmdb?color=success&style=flat-square&label=MMDB)](https://www.npmjs.com/package/@ip-location-db/dbip-city-mmdb) | [City](CITY.md) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) <br> by [DB-IP](https://db-ip.com/) | Monthly | [CSV.gz](https://unpkg.com/@ip-location-db/dbip-city/dbip-city-ipv4.csv.gz)<br>[CSV.7z](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-city-7z/dbip-city-ipv4.csv.7z)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-city-mmdb/dbip-city-ipv4.mmdb) | [CSV.gz](https://unpkg.com/@ip-location-db/dbip-city/dbip-city-ipv6.csv.gz)<br>[CSV.7z](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-city-7z/dbip-city-ipv6.csv.7z)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-city-mmdb/dbip-city-ipv6.mmdb) | [CSV.gz](https://unpkg.com/@ip-location-db/dbip-city/dbip-city-ipv4-num.csv.gz)<br>[CSV.7z](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-city-7z/dbip-city-ipv4-num.csv.7z) | [CSV.gz](https://unpkg.com/@ip-location-db/dbip-city/dbip-city-ipv6-num.csv.gz)<br>[CSV.7z](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-city-7z/dbip-city-ipv6-num.csv.7z) |
| [GeoLite2](https://dev.maxmind.com/geoip/geoip2/geolite2/)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/geolite2-city?color=success&style=flat-square&label=GZ)](https://www.npmjs.com/package/@ip-location-db/geolite2-city)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/geolite2-city-7z?color=success&style=flat-square&label=7z)](https://www.npmjs.com/package/@ip-location-db/geolite2-city-7z)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/geolite2-city-mmdb?color=success&style=flat-square&label=MMDB)](https://www.npmjs.com/package/@ip-location-db/geolite2-city-mmdb) | [City](CITY.md) | GeoLite2 Licence by [MaxMind](https://www.maxmind.com/) | Twice weekly | [CSV.gz](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-city/geolite2-city-ipv4.csv.gz)<br>[CSV.7z](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-city-7z/geolite2-city-ipv4.csv.7z)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-city-mmdb/geolite2-city-ipv4.mmdb) | [CSV.gz](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-city/geolite2-city-ipv6.csv.gz)<br>[CSV.7z](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-city-7z/geolite2-city-ipv6.csv.7z)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-city-mmdb/geolite2-city-ipv6.mmdb) | [CSV.gz](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-city/geolite2-city-ipv4-num.csv.gz)<br>[CSV.7z](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-city-7z/geolite2-city-ipv4-num.csv.7z) | [CSV.gz](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-city/geolite2-city-ipv6-num.csv.gz)<br>[CSV.7z](https://cdn.jsdelivr.net/npm/@ip-location-db/geolite2-city-7z/geolite2-city-ipv6-num.csv.7z) |

## File formats

An explanation of each file format is provided in its own file: [country](COUNTRY.md), [asn](ASN.md), [city](CITY.md).

All files of a given type share the same file format; you could swap one `asn` file for any other `asn` file.

## Which database should I use?

It depends upon your use-case! We do have some simple recommendations though:

- If you need postcodes or timezones: `geolite2-city`
- If you need city data with a CC-BY Licence: `dbip-city`
- If you need a country database with a Public Domain licence: `geo-whois-asn-country` 
- If you need an ASN database: `asn`

## MMDB Libraries 

If you would like to integrate MMDB files into an existing project there are several libraries that can help:

### Read MMDB files

We can use libraries in many languages when using the MMDB files. There are [Maxmind developed libraries](https://github.com/maxmind) for many popular languages: [.NET](https://github.com/maxmind/MaxMind-DB-Reader-dotnet), [C](https://github.com/maxmind/libmaxminddb), [Java](https://github.com/maxmind/GeoIP2-java), [Node.js](https://github.com/maxmind/GeoIP2-node), [Perl](https://github.com/maxmind/MaxMind-DB-Reader-ruby), [PHP](https://github.com/maxmind/MaxMind-DB-Reader-php), [Python](https://github.com/maxmind/MaxMind-DB-Reader-python) and [Ruby](https://github.com/maxmind/MaxMind-DB-Reader-ruby), and third-party readers for others: [Erlang](https://github.com/g-andrade/locus), [Go](https://github.com/oschwald/maxminddb-golang), [Rust](https://github.com/oschwald/maxminddb-rust).

### Write MMDB files

If you wish to create your own MMDB files from the CSV files *(to customise their format)* there are a couple of official libraries: [Go](https://github.com/maxmind/mmdbwriter) and [Perl](https://github.com/maxmind/MaxMind-DB-Writer-perl) *(now archived)*. There are also some third-party options: [Python](https://github.com/VimT/MaxMind-DB-Writer-python) and [Rust](https://github.com/pierd/maxminddb-writer).

## Useful applications

| Application | Language | Description | Types | IPv4 | IPv6 | Auto<br>Updates|
|---|---|---|---|---|---|---|
|[`ip_location_server`](https://github.com/EP-u-NW/ip_location_server) | Java | An in-memory GRPC and HTTP server mapping IP addresses to locations *(requires at least 1.5GB RAM)* | `country`<br>`asn`<br>`city` | ✓ | ✓ | ✓ |
|[`ip-location-api`](https://github.com/paul-norman/ip-location-api) | Go | API server creating / supporting MMDB, PostgreSQL, MySQL / MariaDB and SQLite | `country`<br>`asn`<br>`city` | ✓ | ✓ | ✓ |
|[`Ip-geo-API`](https://github.com/realchandan/Ip-geo-API) | Go | In-memory API server | `country`  | ✓ | ✓ | ✘ |
|[`IPInfoOffline`](https://www.nirsoft.net/utils/ip_country_info_offline.html) | Windows  | Desktop tool showing information about IP addresses *(local data)* | `country`<br>`asn`<br>`city` | ✓ | ✓ | ✘ |

## Useful tools

| Tool | Description |
|---|---|
|[`ip-location-to-mmdb`](https://github.com/paul-norman/ip-location-to-mmdb) | Basic conversion from CSV files from this database into MMDB files |
|[`mmdbmeld`](https://github.com/safing/mmdbmeld) | Create and customise MMDB files from CSV files in this database |

## Licences

The required licence depends upon the database which you use. Please carefully read each database licence before use.

You can use [PDDL](https://opendatacommons.org/licenses/pddl/1.0/) (ODC Public Domain Dedication and Licence) or [CC0](https://creativecommons.org/publicdomain/zero/1.0/deed) (Creative Commons Zero) licensed database without attribution for any purpose.

## Support

We'd be grateful if you could link back to [sapics/ip-location-db](https://github.com/sapics/ip-location-db), and star this project to help others find it.
