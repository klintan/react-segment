# react-segment
Segment.io integration for React.js


### Installation

```
// with npm
$ npm install react-segment --save

// with yarn
$ yarn add react-segment
```

Getting started
---------------

If you're developing using npm and CommonJS modules:

```jsx
let analytics = require('react-segment');

if(process.env.NODE_ENV == 'development'){
    analytics.load("DEVELOPMENT KEY");
}else if(process.env.NODE_ENV == 'staging' ){
    analytics.load("STAGING KEY");
}else if(process.env.NODE_ENV == 'pre-production'){
    analytics.load("PRE-PRODUCTION KEY");
}else if(process.env.NODE_ENV == 'production'){
    analytics.load("PRODUCTION KEY");
}
```

Don't see your prop? explaining your use case, and I will add it.


Issues
------
Please [file an issue](https://github.com/anishmprasad/react-segment/issues) if you find a bug, or need help.


License
-------
The MIT License (MIT)

Copyright (c) 2020 Anish M Prasad
