# Makefile for the focaltech touchscreen drivers.
ccflags-y += $(DISABLE_LTO_CLANG) $(DISABLE_CFI_CLANG) -fno-data-sections -fno-function-sections

obj-$(CONFIG_TOUCHSCREEN_FTS)	+=  focaltech_core.o
obj-$(CONFIG_TOUCHSCREEN_FTS)	+=  focaltech_ex_fun.o
obj-$(CONFIG_TOUCHSCREEN_FTS)	+=  focaltech_ex_mode.o
obj-$(CONFIG_TOUCHSCREEN_FTS)	+=  focaltech_gesture.o
obj-$(CONFIG_TOUCHSCREEN_FTS)	+=  focaltech_esdcheck.o
obj-$(CONFIG_TOUCHSCREEN_FTS)   +=  focaltech_point_report_check.o


obj-$(CONFIG_TOUCHSCREEN_FTS)	+=  focaltech_flash.o
obj-$(CONFIG_TOUCHSCREEN_FTS)   +=  focaltech_flash/focaltech_upgrade_ft3418.o



obj-$(CONFIG_TOUCHSCREEN_FTS)   +=  focaltech_i2c.o
