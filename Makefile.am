bin_PROGRAMS = helloworld

helloworld_SOURCES = hello.c world.c

helloworld_CFLAGS = -g $(AM_CFLAGS) $(fuse_CFLAGS) $(curl_CFLAGS) $(json_CFLAGS) $(xml_CFLAGS)

helloworld_LDADD = $(fuse_LIBS) $(curl_LIBS) $(json_LIBS) $(xml_LIBS)

EXTRA_DIST = COPYING README
