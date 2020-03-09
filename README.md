# @mycv/f8-notification

> Using the Notifications API

[![NPM](https://img.shields.io/npm/v/@mycv/f8-notification.svg)](https://www.npmjs.com/package/@mycv/f8-notification) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save @mycv/f8-notification

// or

yarn add @mycv/f8-notification
```

## Usage

```jsx
import React, { useEffect } from 'react';

import { initNotifications, notify } from '@mycv/f8-notification';

function Example() {
  
  useEffect(() => {
    // request after 3 seconds
    initNotifications({ cooldown: 3000 });
  }, []);

  const showNotification = () => {
    notify('Your title', { body: 'Your message.' });
  }

  return null;
  
}
```

## License

MIT © [sondn](https://github.com/sondnpt00343)
# f8-notification
