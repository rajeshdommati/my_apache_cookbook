# mycookbook-cookbook

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
    <td><tt>['mycookbook']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### mycookbook::default

Include `mycookbook` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[mycookbook::default]"
  ]
}
```

## License and Authors

Author:: Rajesh Dommati (Rajesh.Dommati3@target.com)
