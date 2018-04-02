GCC_VERSION      := $(shell $(CONFIG_SHELL) $(PWD)/scripts/gcc-version.sh $(CROSS_COMPILE)gcc)
EXTRA_CFLAGS += -Idrivers/media/video/msm
EXTRA_CFLAGS += -Idrivers/media/video/msm/io
EXTRA_CFLAGS += -Idrivers/media/video/msm/csi
EXTRA_CFLAGS += -Idrivers/media/video/msm/yushanII
obj-$(CONFIG_MSM_CAMERA_SENSOR) += msm_sensor.o
obj-$(CONFIG_OV5647) += ov5647_v4l2.o
obj-$(CONFIG_IMX091) += imx091_v4l2.o
obj-$(CONFIG_IMX105) += imx105_v4l2.o
obj-$(CONFIG_IMX175) += imx175_v4l2.o
obj-$(CONFIG_MACH_ELITE) += imx175_2lane_v4l2.o
obj-$(CONFIG_MACH_JET) += imx175_2lane_v4l2.o
obj-$(CONFIG_IMX135) += imx135_v4l2.o
ifdef CONFIG_CAMERA_IMAGE_NONE_BOARD
obj-$(CONFIG_OV4688) += ov4688_non_v4l2.o
obj-$(CONFIG_VD6869) += vd6869_non_v4l2.o
else
obj-$(CONFIG_OV4688) += ov4688_v4l2.o
obj-$(CONFIG_VD6869) += vd6869_v4l2.o
endif
obj-$(CONFIG_OV8838) += ov8838_v4l2.o
obj-$(CONFIG_S5K3H2YX) += s5k3h2yx_v4l2.o
obj-$(CONFIG_S5K6A1GX) += s5k6a1gx_v4l2.o
obj-$(CONFIG_AR0260) += ar0260_v4l2.o
obj-$(CONFIG_IMX074) += imx074_v4l2.o
obj-$(CONFIG_S5K3L1YX) += s5k3l1yx.o
obj-$(CONFIG_OV2720) += ov2720.o
obj-$(CONFIG_MT9M114) += mt9m114_v4l2.o
obj-$(CONFIG_S5K4E1) += s5k4e1_v4l2.o
obj-$(CONFIG_MT9E013) += mt9e013_v4l2.o
obj-$(CONFIG_WEBCAM_OV9726) += ov9726_v4l2.o
obj-$(CONFIG_OV7692) += ov7692_v4l2.o
obj-$(CONFIG_VX6953) += vx6953.o
obj-$(CONFIG_OV9724) += ov9724_v4l2.o
obj-$(CONFIG_AVDEVICE) += avdevice.o
