# html

HTML notes!

## `option`
### [Have a null default value on the `option` element](https://stackoverflow.com/a/23638053/6630464)
A little note: the solution above returns an error about the `option` element having a `selected` attribute.
I use the following solution instead:
```
<select defaultValue='null'>
  <option disabled value='null'>-- select --</option>
</select>
```
