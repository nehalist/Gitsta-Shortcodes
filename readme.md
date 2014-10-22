Gitsta Shortcodes
======
Yet another shortcode plugin for WordPress. Mainly for bootstrap.

### Download
- [GitHub Releases](https://github.com/HirczyK/Gitsta-Shortcodes/releases)

### Shortcodes
#### Icons
`[icon family="fa" name="code"]`  
`[icon family="octicon" name="flame" additional="mega-octicon"]`  
`[icon name="twitter"]`  
`[icon family="glyphicon" name="envelope"]`

Parameter | Type | Default | Options
--- | --- | --- | ---
`family` | String | fa | fa, oction, glyphicon
`name` | String | question-circle | *
`additional` | String | "" | *

##### Input
`[kbd]ctrl + e[/kbd]`

##### Labels
`[label type="success"]Label[/label]`

Parameter | Type | Default | Options
--- | --- | --- | ---
`type` | String | default | default, primary, success, info, warning, danger

##### Badges
`[badge]42[/badge]`

##### Progress bars
`[progress-bar value=50 label="false" type="success"]`

Parameter | Type | Default | Options
--- | --- | --- | ---
`value` | Integer | 0 | *
`label` | Bool | true | true, false
`type` | String | "" | default, primary, success, warning, danger

##### Media
`[media img="http://placehold.it/128x128" title="Hello World"]Hello World[/media]`

Parameter | Type | Default | Options
--- | --- | --- | ---
`img` | String | "" | *
`title` | String | "" | *

##### Tooltips
`[tooltip title="Hello World" placement="right"]Hover me![/tooltip]`

Parameter | Type | Default | Options
--- | --- | --- | ---
`title` | String | "" | *
`placement` | String | top | top, right, bottom, left

###### Alerts
`[alert]Alert![/alert]`  
`[alert type="success"]Alert![/alert]`

Parameter | Type | Default | Options
--- | --- | --- | ---
`type` | String | info | info, success, warning, danger

##### Buttons
`[button url="http://www.google.at" type="info" size="lg"]Google-Link[/button]`

Parameter | Type | Default | Options
--- | --- | --- | ---
`type` | String | default | default, primary, success, info, warning, danger, link
`url` | String | # | *
`size` | String | "" | lg, sm, xs

##### Grid
`[row]
[col size="6"]Column 1[/col]
[col size="6"]Column 2[/col]
[/row]`

Parameter | Type | Default | Options
--- | --- | --- | ---
`size` | Integer | 12 | 1 - 12
