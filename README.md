# sonosblue

Sonos hardware does not support bluetooth. The suggested solution seems to be using [Logitech Wireless Speaker Adapter for Bluetooth](http://www.amazon.com/Logitech-Wireless-Speaker-Adapter-Bluetooth/dp/B004VM1T5S), as outlined here [Setup of Logitech Wireless Speaker Adapter for Bluetooth Audio Devices With Sonos](https://sonos.custhelp.com/app/answers/detail/a_id/1790/kw/bluetooth).

That solution is very limited, as it:
* does not provide multiple bluetooth targets
* works only with line-in enabled speakers
* requires standalone peripheral

Enter this effort. It should be possible to hack it together, on bluetooth capable home server / rapsberry pi.

# Contributing

1. Fork it
1. Create your feature branch (`git checkout -b my-new-feature`)
1. Ensure that you add ChefSpec test coverage, and any relevant modifications to the `.kitchen.yml`.
1. Commit your changes (`git commit -am 'Add some feature'`)
1. Push to the branch (`git push origin my-new-feature`)
1. Create new Pull Request

# Author

- Author: Marcin Sawicki (<odcinek@gmail.com>)
- Copyright:: (c) 2015, Marcin Sawicki

```text
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

