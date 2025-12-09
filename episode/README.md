## GraphQL Query

The GraphQL query is defined in `episode-page-1.graphql`

```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
	}
}
```

## Response

The response is defined in `character-id-1-output.json`.

```json
{
  "data": {
    "episode": {
      "id": "1",
      "name": "Pilot",
      "air_date": "December 2, 2013",
      "episode": "S01E01"
    }
  }
}
```
