# Hello world JavaScript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: oskdin/Hello-world-javascript-action@96defb3eb6c6e2c0f639ab2a8dddf62ad55d7ec0
with:
  who-to-greet: 'everybody'
```
