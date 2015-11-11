# Data Lasso

Data Lasso is a visualization tool that allows exploration of arbitrary set of data. It is built to be agnostic to the structure and formatting of data.

### Usage

#### Standalone

Data Lasso can be be used as a standalone itself to explore arbitrary data sets. Data Lasso runs entirely in a browser, so this repository  contains everything necessary to get started.

Checkout the repository locally, run `npm install` to install necessary dependencies and then



#### As part of another system

#### Data formatting

Any CSV, TSV or JSON will do. Data Lasso will try to silently parse field with name `ip` into ip subnets on file upload. Field named `email` will be parsed to extract domain. Field named `geo` will be broken down onto city and country.

#### Visualization

Visualization makes use of 3 spatial spatial dimensions and color. Any attribute associated with a data entry can be used for plotting in any of the 4 dimensions.

### Support

_To be added_


### License

Copyright 2015 Tumblr Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
