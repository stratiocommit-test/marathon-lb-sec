# Changelog

## 0.4.0 (upcoming)

* Adapt repo to new versioning flow
* [EOS-1819] Download certificates only of new deployed apps
* [EOS-1818] Download apps certificates following multitenant convention
* [EOS-1817] Look for marathon-lb own cert following multitenant convention, fall back to "default" path if not found
* [EOS-1825] Fix logger in haproxy_wrapper.py
* [EOS-1816] Add new thread to renew vault token and fix token expire_time calculation
* [EOS-1810] Include checking vault token state in healthcheck
* Fix curl dependency and gpg keyserver in Dockerfile
* [EOS-1074] Fix to tcplog format in tcp backends
* Fix isolate failed backends when regenerating config

## 0.3.1 (March 06, 2018)

* [EOS-1074] Fix to tcplog format in tcp backends
* Fix isolate failed backends when regenerating config

## 0.3.0 (February 20, 2018)

* [EOS-987] Marathon-lb-sec logging format should comply with standard
* [EOS-987] Included b-log version 0.4.0
* [EOS-987] Python, bash, and HAproxy with standard centralized log format
* [EOS-1023] Bug fixing with dead connections to Vault
* [EOS-1038] Output marathon-lb-sec logs to stdout
* [EOS-1067] Ensure the default marathon-lb certificate to be present by SNI if there's no certificate for the concrete app
* [EOS-1068] Updated kms_utils version to 0.4.0
* [EOS-1069] Add CA-bundle to the container
* Add iptables rules in position 2 if a calico rule is present
* Updated Marathon-LB main version v1.11.3
* Bug fixing with race conditions

## 0.2.0 (December 19, 2017)

* [EOS-852] Expose certificates per app
* Python kms_utils wrapper
* Updated kms_utils version to 0.3.0

## 0.1.0 (November 22, 2017)

* [EOS-568] Implement dynamic authentication in Marathon-lb entrypoint
* Marathon-LB main version v1.10.3
