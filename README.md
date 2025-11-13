# [Loggly API](http://loggly-api.hive.pt)

Simple Python API client for Loggly.

## Configuration

| Name | Type | Description |
| ----- | ----- | ----- |
| **LOGGLY_TOKEN** | `str` | The secret token to be for authentication on the Loggly API (defaults to `None`). |
| **LOGGLY_BUFFER_SIZE** | `int` | The size of the buffer (in number of entries) until the buffer is flushed (defaults to `128`). |
| **LOGGLY_TIMEOUT** | `int` | The timeout in seconds in seconds until the buffer is flushed (defaults to `30`). |

## License

Loggly API is currently licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/).

## Build Automation

[![Build Status](https://github.com/hivesolutions/loggly-api/workflows/Main%20Workflow/badge.svg)](https://github.com/hivesolutions/loggly-api/actions)
[![Coverage Status](https://coveralls.io/repos/hivesolutions/loggly-api/badge.svg?branch=master)](https://coveralls.io/r/hivesolutions/loggly-api?branch=master)
[![PyPi Status](https://img.shields.io/pypi/v/loggly-api.svg)](https://pypi.python.org/pypi/loggly-api)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://www.apache.org/licenses/)
