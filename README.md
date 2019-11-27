Run the following commands to recreate the error. Tested on 6.13.1 and 6.7.0

1. (cd packageC && npm i) // good - creates a package-lock.json
2. (cd packageC && npm ci) // error - ENOENT