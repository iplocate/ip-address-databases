# IP address databases by IPLocate.io

Free full IP address databases and database samples from [**IPLocate.io**](https://www.iplocate.io).

## Free IP to Country database

**Get the country and continent for any IP address**

This database is ideal for applications needing accurate country-level geolocation. This database comes from the same accurate, high-quality data that powers the [IPLocate.io API](https://www.iplocate.io/api).

The database is available in CSV and MMDB formats in the [**ip-to-country**](https://github.com/iplocate/ip-address-databases/tree/main/ip-to-country) folder.

**Database Format (CSV):**

| Field            | Description                        | Example              |
| ---------------- | ---------------------------------- | -------------------- |
| `network`        | IP address range in CIDR notation  | `104.220.212.249/32` |
| `continent_code` | Two-letter continent code          | `NA`                 |
| `country_code`   | Two-letter ISO 3166-1 alpha-2 code | `US`                 |
| `country_name`   | Full country name                  | `United States`      |

## Free IP to ASN database

**Get the ASN details for any IP address**

This database maps IP address network ranges to their Autonomous System Number (ASN) details.

The database is available in CSV and MMDB formats in the [**ip-to-asn**](https://github.com/iplocate/ip-address-databases/tree/main/ip-to-asn) folder.

**Database Format (CSV):**

| Field          | Description                        | Example            |
| -------------- | ---------------------------------- | ------------------ |
| `network`      | IP address range in CIDR notation  | `1.0.4.0/22`       |
| `asn`          | Autonomous System Number           | `38803`            |
| `country_code` | Two-letter ISO 3166-1 alpha-2 code | `AU`               |
| `name`         | Network name assignment            | `GTELECOM-AS-AP`   |
| `org`          | Organization of the ASN holder     | `Gtelecom Pty Ltd` |
| `domain`       | Domain of the ASN holder           | `gtelecom.com.au`  |

## License for free IP address databases

The free IP address databases (IP to Country and IP to ASN) provided in this repository are licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

[![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)

This means you are free to use, share, and adapt these databases for any purpose, including commercially, as long as you provide appropriate attribution to IPLocate.io.

**Attribution Requirement:**
You must give appropriate credit by providing a link to [IPLocate.io](https://www.iplocate.io) on your application, product, or website where the data is used. For example: "IP address data powered by [IPLocate.io](https://www.iplocate.io)".

## Premium IP address databases

For more comprehensive and highly accurate IP intelligence data, IPLocate.io offers several premium downloadable databases. Our premium data provides industry-leading accuracy, crucial for mission-critical applications.

Explore our full range of premium databases at: [**https://www.iplocate.io/products/downloadable-databases**](https://www.iplocate.io/products/downloadable-databases)

Our offerings include:

- Full IP to Geolocation database (Country, Region, City, Postal Code, Lat/Lon)
- Full IP to ASN and ASN details database
- IP to Company database
- IP to Hosting/Datacenter database
- Threat and Privacy detection database (proxy, spam, abuse, VPN, Tor, Private Relay detection)
- Abuse contact database
- Complete WHOIS databases (from all RIRs and RWHOIS)

## Fast, free IP geolocation API

Need data on-demand? Look up detailed information about an IP address using the free [**IPLocate.io API**](https://www.iplocate.io):

- [IP geolocation data](https://www.iplocate.io/docs#data-base-data) (IP to city, IP to country, IP to region, postal code, latitude, and longitude)
- [ASN details](https://www.iplocate.io/docs#data-asn-data) (ISP or network operator, associated domain name, and type, such as business, hosting, or company)
- [Privacy & threat data](https://www.iplocate.io/docs#data-privacy-data) (VPN detection, proxy detection, iCloud Private Relay detection, spam and abuser detection)
- [Company data](https://www.iplocate.io/docs#data-company-data) (the name and domain of the business that uses the IP address)

See what information we can provide for [your IP address](https://www.iplocate.io/what-is-my-ip).

IPLocate.io provides 1,000 free requests per day with a [free account](https://iplocate.io/signup). For higher plans and access to more data, check out [API pricing](https://www.iplocate.io/pricing).

We have comprehensive [documentation](https://www.iplocate.io/docs) with quick-start guides and client libraries for many popular programming languages.

## About IPLocate.io

Founded in 2017, IPLocate.io aims to be the most reliable and accurate source of IP address data. We process billions of API requests a month for thousands of businesses and developers of all sizes, providing crucial IP intelligence for security, personalization, compliance, and more.
