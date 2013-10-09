lib_LTLIBRARIES = libappindicator3sharpglue-12.10.0.la

libappindicator3sharpglue_12_10_0_la_SOURCES =

nodist_libappindicator3sharpglue_12_10_0_la_SOURCES = generated.c

libappindicator3sharpglue_12_10_0_la_LDFLAGS = -module -avoid-version -no-undefined

libappindicator3sharpglue_12_10_0_la_LIBADD = $(APPINDICATOR3_LIBS)

INCLUDES = $(APPINDICATOR3_CFLAGS) -I$(top_srcdir)

libappindicator3sharpglue.dll: $(libappindicator3sharpglue_12_10_0_la_OBJECTS) libappindicator3sharpglue.rc libappindicator3sharpglue.def
	./build-dll libappindicator3sharpglue $(VERSION)

CLEANFILES = lib*.a lib*.dll

EXTRA_DIST =
