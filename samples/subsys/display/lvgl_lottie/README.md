# LVGL Lottie example

This sample is a port of the LVGL Lottie example to Zephyr: https://docs.lvgl.io/9.2/widgets/lottie.html#example

The raw Lottie data was generated using the tool provided with LVGL. It's run from this example's
source directory:

    $ python  ../../../../../../modules/lib/gui/lvgl/scripts/filetohex.py \
        lv_example_lottie_approve.json --filter-character --null-terminate \
        > lv_example_lottie_approve.txt
