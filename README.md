# ml2en npm package

An algorithm to transliterate Malayalam script to Roman / Latin characters (commonly 'Manglish') with reasonable phonetic fairness

Installation

```
npm install ml2en
```

Basic Usage
```
var ml2en = require('ml2en');

// malayalam string to be converted
var str = "വ്യാഴത്തിന്റെ കാന്തികക്ഷേത്രം സൗരവാതത്തെ ചെറുക്കുന്ന മേഖലയാണ്‌ വ്യാഴത്തിന്റെ കാന്തമണ്ഡലം.";

// result
var result = ml2en(str);
```

*Malaylam to English transliteration script created by [Kailash Nadh](https://nadh.in/)*.
*Made into an npm package for Node.js use by [Khaleel Gibran](https://khaleelgibran.com)*.