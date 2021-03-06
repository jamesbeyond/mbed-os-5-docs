## Compiling the code

1. Get the code

   From your command-line, import the example:

   ```console
   $ mbed import https://github.com/ARMmbed/mbed-os-quick-start-blinky
   $ cd mbed-os-quick-start-blinky
   ```

1. Compile and program your board:

   1. Invoke `mbed compile`, and specify the name of your platform and your installed toolchain (`GCC_ARM`, `ARM`, `IAR`). For example, for the K64F platform and Arm Compiler 5 toolchain:

       ```console
       $ mbed compile --target K64F --toolchain ARM --flash
       ```  

   The `--flash` argument automatically flashes the compiled program onto your board if it is connected to your computer.

   <span class="tips">**Tip:** You can get the name of the board plugged into your computer by running `mbed detect`, and you can get a full list of supported toolchains and targets by running the `mbed compile --supported` command.</span>

1. Press the board's reset button. The LED blinks.
