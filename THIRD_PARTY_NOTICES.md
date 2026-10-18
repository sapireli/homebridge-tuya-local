# Third-party notices

## Sensor mappings from homebridge-tuya-platform

The contact, smoke, and leak sensor mappings and shared battery mappings in
`lib/TuyaSensorAccessory.js`, `lib/ContactSensorAccessory.js`,
`lib/SmokeSensorAccessory.js`, and `lib/LeakSensorAccessory.js` are adapted from
[0x5e/homebridge-tuya-platform](https://github.com/0x5e/homebridge-tuya-platform),
revision `ab74ea4eee3c9df0be2ecc04c0fc56d9c0b02207`:

- `src/accessory/ContactSensorAccessory.ts`
- `src/accessory/SmokeSensorAccessory.ts`
- `src/accessory/LeakSensorAccessory.ts`
- `src/accessory/BaseAccessory.ts`

Credit goes to 0x5e and the Tuya Homebridge contributors for those implementations.
Eliran Sapir ([sapireli](https://github.com/sapireli)) adapted them for Tuya Plus's
accessory lifecycle, cloud updates, configuration UI, and regression tests.

The source project's MIT license notice follows:

The MIT License (MIT)

Copyright (c) 2014-2021 Tuya Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
