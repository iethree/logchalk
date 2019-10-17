# logchalk

This is a stupid simple wrapper for chalk to get colored console logs.

## Usage
```
const log = require('logchalk');

log.info('info'); //blue
log.success('success'); //green
log.warn('warn'); //yellow
log.err('error'); //red
log.debug('debug'); //purple background
log.log('console log'); //standard console output color
```