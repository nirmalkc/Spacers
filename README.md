# Spacers
A wide variety of margin and padding utility classes to manipulate your UI element spacing in a most easiest way

## Syntax
`spacer-{property}-{side}-{size}`

### Property
m - for margin
p - for padding

### Sides
`t` - for `top`

`r` - for `right`

`b` - for `bottom`

`l` - for `left`

`x` - for both `left` and `right` sides

`y` - for both `top` and `bottom` sides

### Sizes
<table>
	<thead>
		<tr>
			<th>Size</th>
			<th>Value</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>xs</td>
			<td>4px</td>
		</tr>
		<tr>
			<td>sm</td>
			<td>8px</td>
		</tr>
		<tr>
			<td>nm</td>
			<td>16px</td>
		</tr>
		<tr>
			<td>md</td>
			<td>24px</td>
		</tr>
		<tr>
			<td>lg</td>
			<td>32px</td>
		</tr>
		<tr>
			<td>xl</td>
			<td>48px</td>
		</tr>
		<tr>
			<td>xxl</td>
			<td>64px</td>
		</tr>
	</tbody>
</table>

## Examples
### Padding - all sides

`<div class="spacer-p-sm"></div>` - Small

`<div class="spacer-p-nm"></div>` - Normal

`<div class="spacer-p-md"></div>` - Medium

`<div class="spacer-p-lg"></div>` - Large

`<div class="spacer-p-none"></div>` - No padding

### Margin - all sides

Works only for block or inline block level elements. Does not work with inline elements.

`<div class="spacer-m-sm"></div>` - Small

`<div class="spacer-m-nm"></div>` - Normal

`<div class="spacer-m-md"></div>` - Medium

`<div class="spacer-m-lg"></div>` - Large

`<div class="spacer-m-none"></div>` - No margin

### Top and Bottom Padding
`<div class="spacer-p-y-sm"></div>` - Small

`<div class="spacer-p-y-base"></div>` - Normal

`<div class="spacer-p-y-md"></div>` - Medium

`<div class="spacer-p-y-lg"></div>` - Large

`<div class="spacer-p-y-none"></div>` - No padding for top and bottom

### Left and Right Margins
`<div class="spacer-m-x-sm"></div>` - Small

`<div class="spacer-m-x-base"></div>` - Normal

`<div class="spacer-m-x-md"></div>` - Medium

`<div class="spacer-m-x-lg"></div>` - Large

`<div class="spacer-m-x-none"></div>` - No margin for left and right side


### Margin or padding for specific side
`<div class="spacer-m-t-sm"></div>` - Small margin at the top

`<div class="spacer-p-b-lg"></div>` - Large padding at the bottom

