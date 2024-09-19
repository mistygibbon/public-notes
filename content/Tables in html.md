
## An simple example
```html
<table>
  <tr>
    <th>First Header</th>
    <th>Second Header</th>
  </tr>
  <tr>
    <td>This is a data cell</td>
    <td>This is also a data cell!</td>
  </tr>
</table>
```
<table>
  <tr>
    <th>First Header</th>
    <th>Second Header</th>
  </tr>
  <tr>
    <td>This is a data cell</td>
    <td>This is also a data cell!</td>
  </tr>
</table>

Don't use tables for page layout

## td element
Like a table cell
Multiple td form a row of cells
```html
<table>
  <td>Hi, I'm your first cell.</td>
  <td>I'm your second cell.</td>
  <td>I'm your third cell.</td>
  <td>I'm your fourth cell.</td>
</table>
```
<table>
  <td>Hi, I'm your first cell.</td>
  <td>I'm your second cell.</td>
  <td>I'm your third cell.</td>
  <td>I'm your fourth cell.</td>
</table>

## tr element
Signifies a row
```html
<table>
  <tr>
    <td>Hi, I'm your first cell.</td>
    <td>I'm your second cell.</td>
    <td>I'm your third cell.</td>
    <td>I'm your fourth cell.</td>
  </tr>
  <tr>
    <td>1</td>
    <td>2</td>
    <td>3</td>
    <td>4</td>
  </tr>
</table>
```
<table>
  <tr>
    <td>Hi, I'm your first cell.</td>
    <td>I'm your second cell.</td>
    <td>I'm your third cell.</td>
    <td>I'm your fourth cell.</td>
  </tr>
  <tr>
    <td>1</td>
    <td>2</td>
    <td>3</td>
    <td>4</td>
  </tr>
</table>

## th element
Signifies a header, use it the same way as td
```html
<table>
  <tr>
    <td>&nbsp;</td>
    <th>Knocky</th>
    <th>Flor</th>
    <th>Ella</th>
    <th>Juan</th>
  </tr>
  <tr>
    <th>Breed</th>
    <td>Jack Russell</td>
    <td>Poodle</td>
    <td>Streetdog</td>
    <td>Cocker Spaniel</td>
  </tr>
  <tr>
    <th>Age</th>
    <td>16</td>
    <td>9</td>
    <td>10</td>
    <td>5</td>
  </tr>
  <tr>
    <th>Owner</th>
    <td>Mother-in-law</td>
    <td>Me</td>
    <td>Me</td>
    <td>Sister-in-law</td>
  </tr>
  <tr>
    <th>Eating Habits</th>
    <td>Eats everyone's leftovers</td>
    <td>Nibbles at food</td>
    <td>Hearty eater</td>
    <td>Will eat till he explodes</td>
  </tr>
</table>
```
<table>
  <tr>
    <td>&nbsp;</td>
    <th>Knocky</th>
    <th>Flor</th>
    <th>Ella</th>
    <th>Juan</th>
  </tr>
  <tr>
    <th>Breed</th>
    <td>Jack Russell</td>
    <td>Poodle</td>
    <td>Streetdog</td>
    <td>Cocker Spaniel</td>
  </tr>
  <tr>
    <th>Age</th>
    <td>16</td>
    <td>9</td>
    <td>10</td>
    <td>5</td>
  </tr>
  <tr>
    <th>Owner</th>
    <td>Mother-in-law</td>
    <td>Me</td>
    <td>Me</td>
    <td>Sister-in-law</td>
  </tr>
  <tr>
    <th>Eating Habits</th>
    <td>Eats everyone's leftovers</td>
    <td>Nibbles at food</td>
    <td>Hearty eater</td>
    <td>Will eat till he explodes</td>
  </tr>
</table>

Allowing cells to span multiple rows and columns
Use colspan and rowspan attributes
```html
<table>
  <tr>
    <th colspan=2>Animals</th>
  </tr>
  <tr>
    <th colspan=2>Hippopotamus</th>
  </tr>
  <tr>
    <th rowspan=2>Horse</th>
    <td>Mare</td>
  </tr>
  <tr>
    <td>Stallion</td>
  </tr>
  <tr>
    <th colspan=2>Crocodile</th>
  </tr>
  <tr>
    <th rowspan=2>Chicken</th>
    <td>Hen</td>
  </tr>
  <tr>
    <td>Rooster</td>
  </tr>
</table>
```
<table>
  <tr>
    <th colspan=2>Animals</th>
  </tr>
  <tr>
    <th colspan=2>Hippopotamus</th>
  </tr>
  <tr>
    <th rowspan=2>Horse</th>
    <td>Mare</td>
  </tr>
  <tr>
    <td>Stallion</td>
  </tr>
  <tr>
    <th colspan=2>Crocodile</th>
  </tr>
  <tr>
    <th rowspan=2>Chicken</th>
    <td>Hen</td>
  </tr>
  <tr>
    <td>Rooster</td>
  </tr>
</table>

## Styling
Using col
```html
<table>
  <colgroup>
    <col>
    <col style="background-color: yellow">
  </colgroup>
  <tr>
    <th>Data 1</th>
    <th>Data 2</th>
  </tr>
  <tr>
    <td>Calcutta</td>
    <td>Orange</td>
  </tr>
  <tr>
    <td>Robots</td>
    <td>Jazz</td>
  </tr>
</table>
```
<table>
  <colgroup>
    <col>
    <col style="background-color: yellow">
  </colgroup>
  <tr>
    <th>Data 1</th>
    <th>Data 2</th>
  </tr>
  <tr>
    <td>Calcutta</td>
    <td>Orange</td>
  </tr>
  <tr>
    <td>Robots</td>
    <td>Jazz</td>
  </tr>
</table>

## Caption
```html
<table>
  <caption>fdsa</caption>
  <colgroup>
    <col>
    <col style="background-color: yellow">
  </colgroup>
  <tr>
    <th>Data 1</th>
    <th>Data 2</th>
  </tr>
  <tr>
    <td>Calcutta</td>
    <td>Orange</td>
  </tr>
  <tr>
    <td>Robots</td>
    <td>Jazz</td>
  </tr>
</table>
```
Use caption element to add description for table contents
<table>
  <caption>fdsa</caption>
  <colgroup>
    <col>
    <col style="background-color: yellow">
  </colgroup>
  <tr>
    <th>Data 1</th>
    <th>Data 2</th>
  </tr>
  <tr>
    <td>Calcutta</td>
    <td>Orange</td>
  </tr>
  <tr>
    <td>Robots</td>
    <td>Jazz</td>
  </tr>
</table>

## thead, tbody and tfoot elements
thead wraps the header
tbody wraps the table contents
tfoot can be used as sum of previous rows

## Nesting tables
```html
<table id="table1">
  <tr>
    <th>title1</th>
    <th>title2</th>
    <th>title3</th>
  </tr>
  <tr>
    <td id="nested">
      <table id="table2">
        <tr>
          <td>cell1</td>
          <td>cell2</td>
          <td>cell3</td>
        </tr>
      </table>
    </td>
    <td>cell2</td>
    <td>cell3</td>
  </tr>
  <tr>
    <td>cell4</td>
    <td>cell5</td>
    <td>cell6</td>
  </tr>
</table>
```
<table id="table1">
  <tr>
    <th>title1</th>
    <th>title2</th>
    <th>title3</th>
  </tr>
  <tr>
    <td id="nested">
      <table id="table2">
        <tr>
          <td>cell1</td>
          <td>cell2</td>
          <td>cell3</td>
        </tr>
      </table>
    </td>
    <td>cell2</td>
    <td>cell3</td>
  </tr>
  <tr>
    <td>cell4</td>
    <td>cell5</td>
    <td>cell6</td>
  </tr>
</table>

## scope attribute
It tells screenreaders what the header is for

## id and headers attribute
Use id at the header element, and use headers attribute at corresponding cells to point the cells at the respective header