
# USA National Park Excursions API Documentation

Documentation for the [Excursions API Server](https://github.com/willgerman/excursions-api-server) project. Built under the OpenAPI 3.1.0 specification using Redocly CLI v1.34.5.

<br/>

## Authors

- Will German ([@willgerman](https://github.com/willgerman))

<br/>

## License

[GNU Affero General Public License v3.0 (or later)](https://www.gnu.org/licenses/agpl-3.0.en.html)

Copyright (C) 2025  William S. German

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as
published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.

<br/>

## API Protocol

1. [Excursions API Server](https://github.com/willgerman/excursions-api-server).

<br/>

#### Coming Soon

- Endpoint Response Examples

<br/>

## Run Locally

The instructions below will guide you through displaying a live preview or outputting a productionized *.html file in your local environment.

#### 1. Clone the repository.

```
git clone https://github.com/willgerman/excursions-api-docs
cd ./excursions-api-docs
```

#### 2. Install dependencies.

The only dependency for this project is [redocly-cli](https://www.npmjs.com/package/@redocly/cli). For this project, install version 1.34.5. It is generally recommended to install this dependency globally, however if you prefer to install it locally then do so.

```
npm install -g @redocly/cli@1.34.5
```

#### 3. Run the preview.

```
redocly preview-docs src/openapi.yaml
```

#### 4. Build the docs.

The `--output` flag may be omitted. It is used to change the name of the generated *.html file.

```
redocly build-docs src/openapi.yaml --output=index.html
```