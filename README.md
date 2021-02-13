# learning-javascript-github-action
Learning to write GitHub Actions, https://docs.github.com/en/actions/creating-actions/creating-a-javascript-action

[![.github/workflows/main.yml](https://github.com/sblack4/learning-javascript-github-action/workflows/.github/workflows/main.yml/badge.svg)](https://github.com/sblack4/learning-javascript-github-action/actions)

## About 
This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```
uses: actions/hello-world-javascript-action@v1.1
with:
  who-to-greet: 'Mona the Octocat'
```
