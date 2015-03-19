# cens-dhcp-cookbook

Sets up the dhcp server for the cens network using [this dhcp cookbook](https://github.com/spheromak/dhcp-cook) (note a local change)

## Supported Platforms

We need only ubuntu 14.04, but should work on most recent ubuntu and debian distros (as well as any other distros supported by the dhcp cookbook)

## Usage

### cens-dhcp::default

After ensuring the `dhcp` data bag exists in chef (and the node you intend to run this on has permission to access it) add this to the node's run list!

## License and Authors

Author:: Steve Nolen (technolengy@gmail.com)

```text
Copyright:: 2014.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
