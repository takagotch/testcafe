### testcafe
---
https://github.com/DevExpress/testcafe

```js
import { Selector } from 'testcafe';
fixture `Getting Started`
  .page `https://devexpress.github.io/testcafe/example`;
  
test('My frist test', async  t => {
 await t
   .typeText('#developer-name', 'John Smith')
   .click('#submit-button')
   
   .expect(Selector('#article-haeder').innerText).eql('Thank you, John Smith!');
});

const macOSInput = Selector('.colmun').find('level').withText('MacOS').child('input');
```

```
testcafe chrome test1.js
```

```
```


