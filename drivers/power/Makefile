#
# Copyright (c) 2009 Wind River Systems, Inc.
# Tom Rix <Tom.Rix at windriver.com>
#
# SPDX-License-Identifier:	GPL-2.0+
#

obj-$(CONFIG_AXP152_POWER)	+= axp152.o
obj-$(CONFIG_AXP209_POWER)	+= axp209.o
obj-$(CONFIG_EXYNOS_TMU)	+= exynos-tmu.o
obj-$(CONFIG_FTPMU010_POWER)	+= ftpmu010.o
obj-$(CONFIG_TPS6586X_POWER)	+= tps6586x.o
obj-$(CONFIG_TWL4030_POWER)	+= twl4030.o
obj-$(CONFIG_TWL6030_POWER)	+= twl6030.o
obj-$(CONFIG_PALMAS_POWER)	+= palmas.o

obj-$(CONFIG_POWER) += power_core.o
ifdef CONFIG_RK_POWER
obj-$(CONFIG_OF_LIBFDT) += power_fdt.o
obj-y += power_rockchip.o
obj-y += fixed.o
endif
obj-$(CONFIG_DIALOG_POWER) += power_dialog.o
obj-$(CONFIG_POWER_FSL) += power_fsl.o
obj-$(CONFIG_POWER_I2C) += power_i2c.o
obj-$(CONFIG_POWER_SPI) += power_spi.o
obj-$(CONFIG_POWER_PWM_REGULATOR) += rockchip_pwm_regulator.o
obj-y += rockchip-io-domain.o
