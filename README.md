# Management Practices Extension Specification

- **Title:** Management Practices
- **Identifier:** https://fiboa.github.io/management-practices/v0.1.0/schema.yaml
- **Property Name Prefix:** management
- **Extension Maturity Classification:** Proposal
- **Owner**: TBD

This extension describes management practices for tillage and cover crop. 

This could eventually expand to include other management practices like fertility, crop protection, manure, irrigation, residue management, etc.

- Examples:
  - [GeoJSON](examples/geojson/)
  - [GeoParquet](examples/geoparquet/)
- [Schema](schema/schema.yaml)
- [Changelog](./CHANGELOG.md)

## Properties

The fields in the table below can be used in these parts of fiboa documents:

- [ ] Collection
- [x] Feature Properties

| Property Name      | Type   | Description |
| ------------------ | ---------- | ----------- |
| management:cover_crop | boolean  | Describe the field... |
| management:cover_crop_type | enum  | Describe the field... |

## Contributing

All contributions are subject to the
[fiboa Code of Conduct](https://github.com/fiboa/specification/blob/main/CODE_OF_CONDUCT.md).
For contributions, please follow the
[fiboa contributing guideline](https://github.com/fiboa/specification/blob/main/CONTRIBUTING.md).

### Running tests

You'll need to install [nodejs and npm](https://nodejs.org/en/download/) to run the tests.
Alternatively, you can also use [yarn](https://yarnpkg.com/) instead of npm.
In this case replace all occurrences of `npm` with `yarn` below.
Additionally, you need Python >= 3.9 installed.

Afterwards, navigate to the root of the specification repository.
Now, install the required test software: `npm install` and `npm run init`

Finally, you can run all tests or subset of them:

- To run all tests: `npm test`
- To check the markdown run: `npm run check-docs`
- To check the examples run: `npm run check-examples`
