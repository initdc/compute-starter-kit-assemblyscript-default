# Compute@Edge default starter kit for AssemblyScript

[![Deploy to Fastly](https://deploy.edgecompute.app/button)](https://deploy.edgecompute.app/deploy)

Get to know the Fastly Compute@Edge environment with a basic starter that demonstrates routing, simple synthetic responses and code comments that cover common patterns.

**For more details about other starter kits for Compute@Edge, see the [Fastly developer hub](https://developer.fastly.com/solutions/starters)**

## Features

* Allow only requests with particular HTTP methods
* Match request URL path and methods for routing
* Build synthetic responses at the edge

## Understanding the code

This starter is intentionally lightweight, and requires no dependencies aside from the [`@fastly/as-compute`](https://www.npmjs.com/package/@fastly/as-compute) npm package. It will help you understand the basics of processing requests at the edge using Fastly. This starter includes implementations of common patterns explained in our [using Compute@Edge](https://developer.fastly.com/learning/compute/assemblyscript/) and [VCL migration](https://developer.fastly.com/learning/compute/migrate/) guides.

The starter doesn't require the use of any backends. Once deployed, you will have a Fastly service running on Compute@Edge that can generate synthetic responses at the edge.

## Security issues

Please see our [SECURITY.md](SECURITY.md) for guidance on reporting security-related issues.
