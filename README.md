<p align="center">
  <img src="./docs/images/banner.png" width=500  alt="project logo"/>
</p>

<div align="center">
  <a href="https://github.com/samsepoil1211/phoneinfoga/actions">
    <img src="https://github.com/samsepoil1211/phoneinfoga/workflows/Build/badge.svg" alt="build status" />
  </a>
  <a href="https://goreportcard.com/report/github.com/samsepoil1211/phoneinfoga/v2">
    <img src="https://goreportcard.com/badge/github.com/samsepoil1211/phoneinfoga/v2" alt="go report" />
  </a>
  <a href="https://codeclimate.com/github/samsepoil1211/phoneinfoga/maintainability">
    <img src="https://api.codeclimate.com/v1/badges/3259feb1c68df1cd4f71/maintainability"  alt="code climate badge"/>
  </a>
  <a href='https://coveralls.io/github/samsepoil1211/phoneinfoga'>
    <img src='https://coveralls.io/repos/github/samsepoil1211/phoneinfoga/badge.svg' alt='Coverage Status' />
  </a>
  <a href="https://github.com/samsepoil1211/phoneinfoga/releases">
    <img src="https://img.shields.io/github/release/samsepoil1211/phoneinfoga.svg" alt="Latest version" />
  </a>
  <a href="https://hub.docker.com/r/samsepoil1211/phoneinfoga">
    <img src="https://img.shields.io/docker/pulls/samsepoil1211/phoneinfoga.svg" alt="Docker pulls" />
  </a>
</div>

<h4 align="center">Information gathering framework for phone numbers</h4>

<p align="center">
  <a href="https://samsepoil1211.github.io/phoneinfoga/">Documentation</a> •
  <a href="https://petstore.swagger.io/?url=https://raw.githubusercontent.com/samsepoil1211/phoneinfoga/master/web/docs/swagger.yaml">API documentation</a> •
  <a href="https://medium.com/@samsepoil1211/phone-number-scanning-osint-recon-tool-6ad8f0cac27b">Related blog post</a>
</p>

## About

PhoneInfoga is one of the most advanced tools to scan international phone numbers. It allows you to first gather basic information such as country, area, carrier and line type, then use various techniques to try to find the VoIP provider or identify the owner. It works with a collection of scanners that must be configured in order for the tool to be effective. PhoneInfoga doesn't automate everything, it's just there to help investigating on phone numbers.

## Current status

This project is stable and production-ready.

You can try out the web client or REST API on the <a href="https://demo.phoneinfoga.crvx.fr/">demo instance</a>. **This is a test service**. Kittens will die if you abuse it. Most of scanners are not configured so you won't get relevant results.

## Features

- Check if phone number exists
- Gather basic information such as country, line type and carrier
- OSINT footprinting using external APIs, phone books & search engines
- Check for reputation reports, social media, disposable numbers and more
- Use the graphical user interface to run scans from the browser
- Programmatic usage with the [REST API](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/sundowndev/phoneinfoga/master/web/docs/swagger.yaml) and [Go modules](https://pkg.go.dev/github.com/sundowndev/phoneinfoga/v2)

## Anti-features

- Does not claim to provide relevant or verified data, it's just a tool !
- Does not allow to "track" a phone or its owner in real time
- Does not allow to get the precise phone location
- Does not allow to hack a phone

## License

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fsundowndev%2FPhoneInfoga.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fsundowndev%2FPhoneInfoga?ref=badge_shield)

This tool is licensed under the GNU General Public License v3.0.

[Icon](https://www.flaticon.com/free-icon/fingerprint-search-symbol-of-secret-service-investigation_48838) made by <a href="https://www.freepik.com/" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a>.

## Support

<div align="center">
  <img src="https://github.com/samsepoil1211/static/raw/main/sponsors.svg?v=c68eba9" width="100%" heigh="auto" />
</div>
