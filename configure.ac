#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.64])
AC_INIT([whatsexeced], [0.0.1-dev], [Yao Zi <ziyao@disroot.org>])
AC_CONFIG_HEADERS([config.h])

AC_CONFIG_FILES([Makefile])

AM_INIT_AUTOMAKE([])

AC_PROG_CC

m4_include([m4/optional_set_cflag.m4])

OPTIONAL_SET_CFLAGS_INIT

OPTIONAL_SET_CFLAGS([-Wall])
OPTIONAL_SET_CFLAGS([-pedantic])

AC_OUTPUT
