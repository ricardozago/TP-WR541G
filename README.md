# TP-WR541G

I had some troubles when updating my WR541G Firmware. I used [this script](https://gist.github.com/teslamint/7688775) to upload firmware to the router (I don't had access to firmware update gui).

To be clear, the firmware is not mine, is from TP-Link, they have all rights, I just upload here to help users. You can (and should) download in [TP-Link website](http://www.tp-link.com/us/download/TL-WR541G.html#Firmware).

To use, rename the last firmware ([wr541gv7_en_4_7_13_up(101203).bin](https://github.com/ricardozago/TP-WR541G/blob/master/wr541gv7_en_4_7_13_up(101203).bin)), to something easy to write like firmware.bin.

And just run the script with:

    ./tplink.sh firmware.bin
