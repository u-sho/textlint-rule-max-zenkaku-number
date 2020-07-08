# textlint-rule-max-zenkaku-number

全角数字の最大桁数を制限するtextlint rule

## Install

Install with [npm](https://www.npmjs.com/):

```sh
npm install textlint-rule-max-zenkaku-number
```

## Usage

Via `.textlintrc`(Recommended)

```json
{
    "rules": {
        "max-zenkaku-number": true
    }
}
```

Via CLI

```sh
textlint --rule max-zenkaku-number README.md
```

### Build

Builds source codes for publish to the `lib` folder.
You can write ES2015+ source codes in `src/` folder.

    npm run build

### Tests

Run test code in `test` folder.
Test textlint rule by [textlint-tester](https://github.com/textlint/textlint-tester).

```sh
npm test
```

## License

MIT © u-sho
