# SPDX-License-Identifier: GPL-2.0

# arm64
DTC_INCLUDE += $(srctree)/arch/$(SRCARCH)/boot/dts/vendor $(srctree)/arch/$(SRCARCH)/boot/dts/vendor/mediatek

# for cust.dtsi
DTC_INCLUDE += $(dir $(src))

# for devicetree overlay
DTC_FLAGS += -@

dtb-$(CONFIG_ARCH_MEDIATEK) += \
	mt6878.dtb \
	mt6897.dtb \
	mt6985.dtb \
	mt6989.dtb
