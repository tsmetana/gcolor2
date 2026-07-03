## Process this file with automake to produce Makefile.in

INCLUDES = \
	-DPACKAGE_DATA_DIR=\""$(datadir)"\" \
	-DPACKAGE_LOCALE_DIR=\""$(prefix)/$(DATADIRNAME)/locale"\" \
	@PACKAGE_CFLAGS@

bin_PROGRAMS = gcolor2

gcolor2_SOURCES = \
	main.c \
	interface.c interface.h \
	callbacks.c callbacks.h \
	support.c support.h

gcolor2_LDADD = @PACKAGE_LIBS@ $(INTLLIBS)

