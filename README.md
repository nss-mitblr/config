# NSS MIT-BLR Configuration Repository

> ⚠️ **Notice:** This repository currently acts as a proof-of-concept, not an MVP or a production-ready application. For further information on the project's status, please refer to [History](#history).

This repository consists of files that are used by our [mobile application](https://github.com/nss-mitblr/app), fetched through the [API](https://github.com/nss-mitblr/api).

## Contributors

- Abhigyan Tripathi [(GitHub)](https://github.com/abhigyantrips) [(LinkedIn)](https://linkedin.com/in/abhigyantrips)

## History

On 13th August, 2024, the team commenced work on an application for the volunteers of NSS MIT-BLR in order to centralize their event contribution and resource management. This application was created with the aim to streamline administrative workflows and reduce the time spent in shift and volunteer hour calculation.

The project was archived on 20th February, 2025 after an elongated period of inactivity from the Core Committee, and inability to provide the hosting resources for the API that accompanies the application.

While we were unable to implement this project successfully, this repository remains public to provide other such endeavours with a headstart.

## Configuration

### Office Bearers Format

```json
{
  "programme_officers": [
    {
      "name": "string",
      "contact": "string",
      "email": "string",
    },
    {
      "...": "..."
    }
  ],
  "unit_heads": [
    {
      "name": "string",
      "contact": "string",
      "email": "string",
    },
    {
      "...": "..."
    }
  ]
}
```

### Contact Details Format

```json
{
  "email": "string"
}
```