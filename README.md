## quotes-factory: Quotes Overloaded Library for JavaScript Developers

quotes-factory is a versatile JavaScript package that provides a comprehensive set of quotes to let you choose the best one for your project.

### Installation

Install quotes-factory using npm, pnpm or yarn:

```bash
npm install quotes-factory
```

```bash
pnpm install quotes-factory
```

```bash
yarn add quotes-factory
```

### Usage

Import the quotes-factory library:

```javascript
// ES5 Import
const getQuotes = require("quotes-factory");

// ES6 Import
import getQuotes from "quotes-factory";
```

### Available Function

quotes-factory offers a wide range of random quotes. Here's how to access them:

- **getQuotes()**: Always provides you with a new random quote that you're definitely going to love.

Get complete quote object

```javascript
const statement = getQuotes().statement;
const author = getQuotes().author;

const quote = `${statement}\n${author}`;

console.log(quote);

// I didn’t fail the test. I just found 100 ways to do it wrong.
// Mark Twain
```

Explore rest of the quotes by installing and utilizing this amazing libraray.

### Supoort

Feel free to contribute and make quotes-factory a better choice.
