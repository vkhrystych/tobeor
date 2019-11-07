# tobeor - simple wrapper for annoying OR statements

Hey! That's my first open-source package, so don't blame on me 😏

#### Philosophy

To be or not to be?
It's very annoying to write OR, value-based statements in JS with a lot of variants like this:

```
const a = 'foo';

if (a === 'foo' || a === 'buz' || a === 'foobuz') {}
```

Instead of this I have made this small package, where you can pass variable and array with value variants:

```
if (tobeor(a, ['foo', 'buz', 'foobuz'])) {}
```

Function just returns true or false and that's it.
Package pretty simple - it's just one line of code, that use .includes() method to check truthfulness of statement.

#### How to install

If you use NPM: `npm i tobeor`

If you use Yarn: `yarn add tobeor`

#### Usage

Just import the package, and use it like a func:

```
import tobeor from 'tobeor';

const foo = 'a';

if (tobeor(foo, ['a', 'b', 'c']));
// This code will return "true"
```

#### Questions

If you have questions or propositions - write me on email: `vladyslavkhrystych@gmail.com`
