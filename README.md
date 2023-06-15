## Database Monitor
A module to quickly check the sizes of the database tables during runtime and set alerts if the tablesize becomes to big.

## Features
- Analyze table sizes during runtime
- Set thresholds to warn/alert on when a tablesize becomes to big

## Dependencies
- none

## Usage
1. Import the module
2. Set the correct administrator userrole for the module
3. Add the SNIP_TableSizes snippet to a page
4. Run the app and click on the Get Sizes button.

*Optional:*
Set warning and critical thresholds for the tables, if crossed it will either log a warning or critical message and change the table status.

## Import notes
This module will only work for Postgres in the cloud or when running a restored postgres database locally!

## Future features
- Easy way to perform vacuum actions
- Add some useful runtime graphs

## Issues, suggestions and feature requests
https://github.com/hunter-koppen/DBSizeChecker/issues