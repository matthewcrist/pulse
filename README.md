## The pulse of the federal .gov webspace

How the .gov domain space is doing at best practices and federal requirements.

## Setup

* Have Bundler installed:

```bash
gem install bundler
```

* Run the following commands to install the necessary packages:

```bash
bundle install
```

* Now you can run the app:

```bash
make run
```

## Ideas for later versions

This project is an initial pass - there is mmuch more information that can be represented in dashboards to great effect.  Below are some of the further ideas for both for future work on this project.  Feel free to add your ideas here, too.

* For the HTTPS Dashboard:
  * Even more HTTPS detail, e.g. SHA-1, forward secrecy
  * Expand to cover subdomains
* For the DAP Dashboard
  * Number of pages from a domain reporting into DAP
  * Number or list of subdomains from a domain reporting into DAP
  * Expand to cover subdomains
  * Test the deeper config options that the DAP snippet should be employing, such as IP anonymization, Event tracking, Demographics turned off, and ?????.  (Possibly using headless browser)
* Does the site require “www”? Does it require not using “www”?
* Load time (server-side)
* Mobile friendliness (poss. using Google's [Mobile Friendly Test](http://www.nextgov.com/mobile/2015/04/here-are-agency-websites-google-doesnt-think-are-mobile-friendly/110812/?oref=ng-relatedstories))
* Mixed content detection (linking to insecure resources)
* Use of third party services
* 508 compliance (poss. with http://pa11y.org/)

### Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
