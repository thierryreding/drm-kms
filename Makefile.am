AUTOMAKE_OPTIONS = subdir-objects

ACLOCAL_AMFLAGS = -I m4

include_HEADERS = \
	src/drm-kms.h

lib_LTLIBRARIES = libdrm-kms.la

libdrm_kms_la_CFLAGS = @DRM_CFLAGS@

libdrm_kms_la_SOURCES = \
	src/drm-kms.c

libdrm_kms_la_LIBADD = @DRM_LIBS@

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = src/drm-kms.pc
