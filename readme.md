# project based on esp-idf 5.01 to support LCD controller GC9A01 and touch sensor cst816s 
 1.this project is based on examples called  spi_lcd_touch of esp-idf

 2.the version of esp-idf is 5.0.1

## steps to build prject
 1.install esp-idf v5.0.1 as [here](https://docs.espressif.com/projects/esp-idf/en/v5.0.1/esp32/get-started/index.html#installation)

 2.modify the pin number as you definiton in your board from lvgl_demo_ui.c

 3.build the firmware and test it

## create from idf examples
 1. copy spi_lcd_touch example from examples/lcd/spi_lcd_touch
 2. run command idf.py add-dependency esp_lcd_touch_cst816s==1.0.1
 3. modify the  Kconfig.projbuild as your wish
 4. modify pin number definition in lvgl_demo_ui.c
 5. build firmware
 

