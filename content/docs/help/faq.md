+++
title = "FAQ"
description = "Answers to frequently asked questions."
date = 2021-05-01T19:30:00+00:00
updated = 2021-05-01T19:30:00+00:00
draft = false
weight = 30
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = "Answers to frequently asked questions."
toc = true
top = false
+++

## What is Pyrinas?

Pyrinas is both a server coded in Rust to bring together all the important features you'd expect from IoT. It's also includes a companion MQTT client for the Zephyr RTOS.

## What hardware can you use with Pyrinas?

Currently Pyrinas supports the nRF9160 Feather fully. Although the MQTT should work on any platform that is Zephyr based some additional work may be required to get it 100%. 

Have a harware platform you'd like to get working? We'd love your help!

## Where can I run Pyrinas Server?

You can run Pyrinas server on any machine that is supported by Rust. Our OS of choice is FreeBSD running Pyrinas Server in a jail. It can be run on Linux and within containers as well! We anticipate future support for Docker containers.

## Contact the creator?

Send *Jared Wolff* an E-mail:

- <hello@jaredwolff.com>
