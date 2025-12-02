# Novu API Postman Collection

Official Postman collection for the [Novu API](https://docs.novu.co/api-reference).

<div align="left">
    <a href="https://www.speakeasy.com/?utm_source=novu-postman&utm_campaign=postman"><img src="https://custom-icon-badges.demolab.com/badge/-Built%20By%20Speakeasy-212015?style=for-the-badge&logoColor=FBE331&logo=speakeasy&labelColor=545454" /></a>
    <a href="https://opensource.org/licenses/MIT">
        <img src="https://img.shields.io/badge/License-MIT-blue.svg" style="width: 100px; height: 28px;" />
    </a>
</div>

## Usage

### Import into Postman

1. Download the collection file from [`postman/novu_api_postman_collection.json`](./postman/novu_api_postman_collection.json)
2. Open Postman
3. Click **Import** → **Upload Files**
4. Select the downloaded JSON file

### Import into Insomnia

1. Download the collection file
2. Open Insomnia
3. Click **Import/Export** → **Import Data** → **From File**
4. Select the downloaded JSON file

## Environment Variables

After importing, create an environment with the following variables:

| Variable | Description |
|----------|-------------|
| `baseUrl` | API base URL (`https://api.novu.co` or `https://eu.api.novu.co`) |
| `secretKey` | Your Novu API secret key |

## Auto-Generation

This collection is automatically generated from the [Novu OpenAPI specification](https://api.novu.co/openapi.sdk.yaml) using [Speakeasy](https://www.speakeasy.com/).

Updates are generated daily and published via pull request.

## Links

- [Novu Documentation](https://docs.novu.co)
- [API Reference](https://docs.novu.co/api-reference)
- [Novu Dashboard](https://dashboard.novu.co)

## License

MIT
