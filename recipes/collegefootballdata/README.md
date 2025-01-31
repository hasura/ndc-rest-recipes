# HTTP Connector configuration for College Football Data API

This configuration is built from [CollegeFootballData.com's OpenAPI Specification](https://collegefootballdata.com/).

## V1

## Usage

Import the schema file, add required environment variables and start the connector.

```yaml
files:
  - file: https://raw.githubusercontent.com/hasura/ndc-http-recipes/refs/heads/main/recipes/collegefootballdata/v1/schema/collegefootballdata.json
    spec: ndc
```

### Environment Variables

| Name         | Description                                  | Default Value |
| ------------ | -------------------------------------------- | ------------- |
| CFBD_API_KEY | API Key for the College Football Data API v1 |               |

### Update schema

Update the latest commit in [v1/generator/schema.yaml](v1/generator/schema.yaml) and run:

```sh
make build-schema-v1
```

## V2

## Usage

Import the schema file, add required environment variables and start the connector.

```yaml
files:
  - file: https://raw.githubusercontent.com/hasura/ndc-http-recipes/refs/heads/main/recipes/collegefootballdata/v2/schema/collegefootballdata.json
    spec: ndc
```

### Environment Variables

| Name         | Description                                  | Default Value |
| ------------ | -------------------------------------------- | ------------- |
| CFBD_API_KEY | API Key for the College Football Data API v2 |               |

### Update schema

Update the latest commit in [v2/generator/schema.yaml](v2/generator/schema.yaml) and run:

```sh
make build-schema-v2
```
