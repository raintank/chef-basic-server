# basic-server-cookbook

TODO: Enter the cookbook description here.

## Supported Platforms

TODO: List your supported platforms.

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['basic-server']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### basic-server::default

Include `basic-server` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[basic-server::default]"
  ]
}
```

## License and Authors

Author:: Raintank Inc. (<jeremy@raintank.io>)
