# open-telemetry-javascript-tutorial

See the tutorial at https://opentelemetry.io/docs/languages/js/

## Usage

```bash
npm install
npm run start
```

## OpenTelemetry

OpenTelemetry is an open source observability framework for collecting telemetry data. It is a collection of libraries, APIs, and tools that can be used to collect telemetry data from your application.

### OpenTelemetry SDK and Auto-instrumentations

The OpenTelemetry SDK is a collection of libraries that can be used to collect telemetry data from your application.
The OpenTelemetry Auto-instrumentations is a collection of libraries that can be used to auto-instrument your application to collect telemetry data from your application.

### OpenTelemetry Libraries

| Library | Description | URL |
|---------|-------------|-----|
| @opentelemetry/api | **OpenTelemetry API for JavaScript** <br> This package provides everything needed to interact with the OpenTelemetry API, including all TypeScript interfaces, enums, and no-op implementations. It is intended for use both on the server and in the browser. | https://www.npmjs.com/package/@opentelemetry/api |
| @opentelemetry/sdk-node | **OpenTelemetry SDK for Node.js** <br> This package provides the full OpenTelemetry SDK for Node.js including tracing and metrics. | https://www.npmjs.com/package/@opentelemetry/sdk-node |
| @opentelemetry/auto-instrumentations-node | **OpenTelemetry Meta Packages for Node** <br> This module provides a way to auto instrument any Node application to capture telemetry from a number of popular libraries and frameworks. You can export the telemetry data in a variety of formats. Exporters, samplers, and more can be configured via environment variables. The net result is the ability to gather telemetry data from a Node application without any code changes. | https://www.npmjs.com/package/@opentelemetry/auto-instrumentations-node |