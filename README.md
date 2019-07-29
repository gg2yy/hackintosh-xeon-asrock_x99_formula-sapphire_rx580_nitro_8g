   This is my complete EFI folder to be used for hackintosh on "ASROCK X99 OC FORMULA" and "ASROCK X99 TAICHI"
   
# Hardware   
   * ASROCK X99 Formula: 
      * https://www.asrock.com/mb/intel/x99%20oc%20formula/
      * http://asrock.pc.cdn.bitgravity.com/Manual/X99%20OC%20Formula.pdf
      * BIOS: 3.40
   * 2 X Sapphire RX-580 nitro+ 8GB oc: https://www.sapphiretech.com/en/consumer/nitro-rx-580-8g-g5
      * "PCIE1": PCI-X 3.0 X16 
      * "PCIE3": PCI-X 3.0 X16
   * XEON E5-2670 V3 2.2Ghz ES stepping 1, 12 cores/24 threads:               
      * Retail: https://ark.intel.com/content/www/us/en/ark/products/81709/intel-xeon-processor-e5-2670-v3-30m-cache-2-30-ghz.html
   * 16 GB DDR4 RAM Corsair 2133 CL 15: https://www.kingston.com/dataSheets/KVR21N15S8_4.pdf
      * quad channel
   * SSD Sandisk plus 240GB at "S_SATA3_1", 6Gb/s
   * BIOS configuration:
   * CPU info: <p align="center">
  <img src="https://github.com/rogeriomm/hackintosh-xeon-asrock_x99_formula-sapphire_rx580_nitro_8g/blob/master/images/screenshot_xeon.jpg?raw=true" alt="MSX fat breakout board"/>
</p>

# Status:
   * Install ok. 
   * MAC OS version
      * Mojave 14.4.5
      * Mojave 14.4.6
      * Catalina TODO
   
# Issues
   * Random boot VRAM error
      * Fixed on https://github.com/acidanthera/WhateverGreen/commit/bcd3f2ef73266f4a320ccfd0686bef2a969b2bde

# Benchmarking
   * Geekbench
      * This machine CPU: https://browser.geekbench.com/v4/cpu/13674426
      * This machine GPU: https://browser.geekbench.com/v4/compute/4217788
      * Dell vostro 347 - I7-8700 3.2Ghz, running Linux Ubuntu 18.04: https://topics-cdn.dell.com/pdf/vostro-3470-desktop_owners-manual4_en-us.pdf
         * https://browser.geekbench.com/v4/cpu/13676390
      * XEON 18 cores/36 threads E5-2696 v3
         * https://browser.geekbench.com/v4/cpu/14048536
