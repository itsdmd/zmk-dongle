# ZMK config for corne-like keyboard with dongle

The config allows you to use 3 n!n, one for the dongle, one for the left half, one for the right half. Using a dongle significantly increases battery life. The dongle can be any device on the nRF52840 (or other supported ZMK controllers). More details on the [slicemk page](https://www.slicemk.com/pages/split-dongle).

## Install

Before flashing this firmware, flash the [setting reset firmware](https://zmk.dev/docs/troubleshooting#split-keyboard-halves-unable-to-pair) into all 3 controllers. Then flash this firmware on 3 devices. If the halves do not connect themselves, try pressing the reset buttons on the dongle and keyboards.

## Credit

* [@slicemk](https://github.com/slicemk) for the original idea

* [@krikun98](https://github.com/krikun98/) for the original repo.
