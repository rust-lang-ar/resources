# resources
Respository for resources created by members of the community.

## History

The `history.json` file keeps track of the meetups, their authors,
topic and resources used.

Every entry in `history.json` have the following fields:

Property | Type | Description
--- | --- | ---
`title` | `String` | Name of the presentation
`author` | `String` | Name of the author
`date` | `String` | The presentation date formatted as `YYYY-MM-DD`
`github` | `Object` | An object containing the `author` GitHub details
`github.login` | `String` | Author's GitHub username
`github.url` | `String` | Author's GitHub URL
`repositories` | `Array<String>` | Repositories used as reference during the presentation
`playground_links` | `Array<String>` | Links to playground instances used during the presentation
`external_resources_links` | `Array<String>` | Links to external resources used during the presentation
`presentations_dir_link` | `String` | Link to the directory behind the `./presentation` directory with files related to the presentation
`tape_url` | `String` | URL to the presentation's tape

### Presentation Details Sample

```json
  {
    "title": "Rust n' Risc V - BarbaOS",
    "author": "Matias Lafroce",
    "date": "2020-08-30",
    "github": {
      "login": "mlafroce",
      "url": "https://github.com/mlafroce"
    },
    "repositories": [
      ""
    ],
    "playground_links": [],
    "external_resources_links": [],
    "presentations_dir_link": "",
    "tape_url": ""
  }
```
