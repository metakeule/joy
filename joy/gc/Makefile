# Generated automatically from Makefile.in by configure.
# Makefile.in generated automatically by automake 1.4 from Makefile.am

# Copyright (C) 1994, 1995-8, 1999 Free Software Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.

# Copyright (c) 1999-2001 by Red Hat, Inc. All rights reserved.
# 
# THIS MATERIAL IS PROVIDED AS IS, WITH ABSOLUTELY NO WARRANTY EXPRESSED
# OR IMPLIED.  ANY USE IS AT YOUR OWN RISK.
# 
# Permission is hereby granted to use or copy this program
# for any purpose,  provided the above notices are retained on all copies.
# Permission to modify the code and to distribute modified code is granted,
# provided the above notices are retained, and a notice that the code was
# modified is included with the above copyright notice.
#
# Original author: Tom Tromey


SHELL = /bin/sh

srcdir = .
top_srcdir = .
prefix = /usr/local
exec_prefix = ${prefix}

bindir = ${exec_prefix}/bin
sbindir = ${exec_prefix}/sbin
libexecdir = ${exec_prefix}/libexec
datadir = ${prefix}/share
sysconfdir = ${prefix}/etc
sharedstatedir = ${prefix}/com
localstatedir = ${prefix}/var
libdir = ${exec_prefix}/lib
infodir = ${prefix}/info
mandir = ${prefix}/man
includedir = ${prefix}/include
oldincludedir = /usr/include

DESTDIR =

pkgdatadir = $(datadir)/gc
pkglibdir = $(libdir)/gc
pkgincludedir = $(includedir)/gc

top_builddir = .

ACLOCAL = aclocal
AUTOCONF = autoconf
AUTOMAKE = automake
AUTOHEADER = autoheader

INSTALL = /usr/bin/install -c
INSTALL_PROGRAM = ${INSTALL} $(AM_INSTALL_PROGRAM_FLAGS)
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_SCRIPT = ${INSTALL_PROGRAM}
transform = s,x,x,

NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_alias = i686-pc-linux-gnu
build_triplet = i686-pc-linux-gnu
host_alias = i686-pc-linux-gnu
host_triplet = i686-pc-linux-gnu
target_alias = i686-pc-linux-gnu
target_triplet = i686-pc-linux-gnu
AR = ar
AS = as
CC = gcc
CPP = @CPP@
CXX = c++
CXXCPP = @CXXCPP@
CXXINCLUDES = 
DLLTOOL = @DLLTOOL@
EXEEXT = 
EXTRA_TEST_LIBS =  -ldl
GCJ = @GCJ@
GCJFLAGS = @GCJFLAGS@
GC_CFLAGS = -fexceptions -I$(top_builddir)/./targ-include -I$(top_builddir)/././libc/include
INCLUDES = -I./include
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LN_S = ln -s
MAINT = #
MAKEINFO = makeinfo
MY_CFLAGS = -g -O2
OBJDUMP = @OBJDUMP@
OBJEXT = @OBJEXT@
PACKAGE = gc
RANLIB = ranlib
STRIP = @STRIP@
THREADLIBS = 
VERSION = 6.0
addobjs =  mach_dep.lo
gc_basedir = ./.
target_all = libgc.la

AUTOMAKE_OPTIONS = cygnus

# Multilib support variables.
MULTISRCTOP = 
MULTIBUILDTOP = 
MULTIDIRS = 
MULTISUBDIR = 
MULTIDO = true
MULTICLEAN = true
toolexeclibdir = $(libdir)$(MULTISUBDIR)
#toolexeclibdir = $(toolexecdir)/lib$(MULTISUBDIR)
#toolexecdir = $(exec_prefix)/$(target_alias)

toolexeclib_LTLIBRARIES = $(target_all)
EXTRA_LTLIBRARIES = libgc.la
libgc_la_SOURCES = allchblk.c alloc.c blacklst.c checksums.c dbg_mlc.c dyn_load.c finalize.c gc_dlopen.c gcj_mlc.c headers.c irix_threads.c linux_threads.c malloc.c mallocx.c mark.c mark_rts.c misc.c new_hblk.c obj_map.c os_dep.c pcr_interface.c ptr_chck.c real_malloc.c reclaim.c solaris_pthreads.c solaris_threads.c specific.c stubborn.c typd_mlc.c


# Include THREADLIBS here to ensure that the correct versions of
# linuxthread semaphore functions get linked:
libgc_la_LIBADD =  mach_dep.lo $(THREADLIBS)
libgc_la_DEPENDENCIES =  mach_dep.lo
libgc_la_LDFLAGS = -version-info 1:1:0 -rpath $(toolexeclibdir)

EXTRA_libgc_la_SOURCES = alpha_mach_dep.s mips_sgi_mach_dep.s mips_ultrix_mach_dep.s powerpc_macosx_mach_dep.s rs6000_mach_dep.s sparc_mach_dep.s sparc_netbsd_mach_dep.s sparc_sunos4_mach_dep.s


AM_CXXFLAGS = -fexceptions -I$(top_builddir)/./targ-include -I$(top_builddir)/././libc/include

AM_CFLAGS = -fexceptions -I$(top_builddir)/./targ-include -I$(top_builddir)/././libc/include

check_PROGRAMS = gctest
gctest_OBJECTS = test.o
gctest_LDADD = ./libgc.la $(THREADLIBS) $(EXTRA_TEST_LIBS)
TESTS_ENVIRONMENT = LD_LIBRARY_PATH=../../$(MULTIBUILDTOP)gcc
TESTS = gctest

all_objs =  mach_dep.lo $(libgc_la_OBJECTS)

LTCOMPILE = $(LIBTOOL) --mode=compile $(CC) $(DEFS) $(INCLUDES) 	$(AM_CPPFLAGS) $(CPPFLAGS) 	$(AM_CFLAGS) $(MY_CFLAGS) $(GC_CFLAGS) 

LINK = $(LIBTOOL) --mode=link $(CC) $(AM_CFLAGS) $(MY_CFLAGS) $(LDFLAGS) -o $@

# Work around what appears to be a GNU make bug handling MAKEFLAGS
# values defined in terms of make variables, as is the case for CC and
# friends when we are called from the top level Makefile.
AM_MAKEFLAGS =  	"AR_FLAGS=$(AR_FLAGS)" 	"CC_FOR_BUILD=$(CC_FOR_BUILD)" 	"CFLAGS=$(CFLAGS)" 	"CXXFLAGS=$(CXXFLAGS)" 	"CFLAGS_FOR_BUILD=$(CFLAGS_FOR_BUILD)" 	"CFLAGS_FOR_TARGET=$(CFLAGS_FOR_TARGET)" 	"INSTALL=$(INSTALL)" 	"INSTALL_DATA=$(INSTALL_DATA)" 	"INSTALL_PROGRAM=$(INSTALL_PROGRAM)" 	"INSTALL_SCRIPT=$(INSTALL_SCRIPT)" 	"LDFLAGS=$(LDFLAGS)" 	"LIBCFLAGS=$(LIBCFLAGS)" 	"LIBCFLAGS_FOR_TARGET=$(LIBCFLAGS_FOR_TARGET)" 	"MAKE=$(MAKE)" 	"MAKEINFO=$(MAKEINFO) $(MAKEINFOFLAGS)" 	"PICFLAG=$(PICFLAG)" 	"PICFLAG_FOR_TARGET=$(PICFLAG_FOR_TARGET)" 	"SHELL=$(SHELL)" 	"EXPECT=$(EXPECT)" 	"RUNTEST=$(RUNTEST)" 	"RUNTESTFLAGS=$(RUNTESTFLAGS)" 	"exec_prefix=$(exec_prefix)" 	"infodir=$(infodir)" 	"libdir=$(libdir)" 	"prefix=$(prefix)" 	"tooldir=$(tooldir)" 	"AR=$(AR)" 	"AS=$(AS)" 	"CC=$(CC)" 	"CXX=$(CXX)" 	"LD=$(LD)" 	"LIBCFLAGS=$(LIBCFLAGS)" 	"NM=$(NM)" 	"PICFLAG=$(PICFLAG)" 	"RANLIB=$(RANLIB)" 	"DESTDIR=$(DESTDIR)"


CONFIG_STATUS_DEPENDENCIES = $(srcdir)/configure.host

MAKEOVERRIDES = 
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_CLEAN_FILES = 
LTLIBRARIES =  $(toolexeclib_LTLIBRARIES)


DEFS =  -DSILENT=1 -DNO_SIGNALS=1 -DNO_EXECUTE_PERMISSION=1 -DALL_INTERIOR_POINTERS=1 -DJAVA_FINALIZATION=1 -DGC_GCJ_SUPPORT=1 -DATOMIC_UNCOLLECTABLE=1  -I. -I$(srcdir) 
CPPFLAGS = 
LDFLAGS = 
LIBS = 
libgc_la_OBJECTS =  allchblk.lo alloc.lo blacklst.lo checksums.lo \
dbg_mlc.lo dyn_load.lo finalize.lo gc_dlopen.lo gcj_mlc.lo headers.lo \
irix_threads.lo linux_threads.lo malloc.lo mallocx.lo mark.lo \
mark_rts.lo misc.lo new_hblk.lo obj_map.lo os_dep.lo pcr_interface.lo \
ptr_chck.lo real_malloc.lo reclaim.lo solaris_pthreads.lo \
solaris_threads.lo specific.lo stubborn.lo typd_mlc.lo
check_PROGRAMS =  gctest$(EXEEXT)
gctest_DEPENDENCIES =  ./libgc.la
gctest_LDFLAGS = 
CFLAGS = -g -O2
COMPILE = $(CC) $(DEFS) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
CCLD = $(CC)
DIST_COMMON =  Makefile.am Makefile.in acinclude.m4 aclocal.m4 \
config.guess config.sub configure configure.in install-sh ltconfig \
ltmain.sh


DISTFILES = $(DIST_COMMON) $(SOURCES) $(HEADERS) $(TEXINFOS) $(EXTRA_DIST)

TAR = gtar
GZIP_ENV = --best
SOURCES = $(libgc_la_SOURCES) $(EXTRA_libgc_la_SOURCES)
OBJECTS = $(libgc_la_OBJECTS)

all: all-redirect
.SUFFIXES:
.SUFFIXES: .S .c .lo .o .obj .s
$(srcdir)/Makefile.in: # Makefile.am $(top_srcdir)/configure.in $(ACLOCAL_M4) 
	cd $(top_srcdir) && $(AUTOMAKE) --cygnus Makefile

Makefile: $(srcdir)/Makefile.in  $(top_builddir)/config.status
	cd $(top_builddir) \
	  && CONFIG_FILES=$@ CONFIG_HEADERS= $(SHELL) ./config.status

$(ACLOCAL_M4): # configure.in  acinclude.m4
	cd $(srcdir) && $(ACLOCAL)

config.status: $(srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	$(SHELL) ./config.status --recheck
$(srcdir)/configure: #$(srcdir)/configure.in $(ACLOCAL_M4) $(CONFIGURE_DEPENDENCIES)
	cd $(srcdir) && $(AUTOCONF)

mostlyclean-toolexeclibLTLIBRARIES:

clean-toolexeclibLTLIBRARIES:
	-test -z "$(toolexeclib_LTLIBRARIES)" || rm -f $(toolexeclib_LTLIBRARIES)

distclean-toolexeclibLTLIBRARIES:

maintainer-clean-toolexeclibLTLIBRARIES:

install-toolexeclibLTLIBRARIES: $(toolexeclib_LTLIBRARIES)
	@$(NORMAL_INSTALL)
	$(mkinstalldirs) $(DESTDIR)$(toolexeclibdir)
	@list='$(toolexeclib_LTLIBRARIES)'; for p in $$list; do \
	  if test -f $$p; then \
	    echo "$(LIBTOOL)  --mode=install $(INSTALL) $$p $(DESTDIR)$(toolexeclibdir)/$$p"; \
	    $(LIBTOOL)  --mode=install $(INSTALL) $$p $(DESTDIR)$(toolexeclibdir)/$$p; \
	  else :; fi; \
	done

uninstall-toolexeclibLTLIBRARIES:
	@$(NORMAL_UNINSTALL)
	list='$(toolexeclib_LTLIBRARIES)'; for p in $$list; do \
	  $(LIBTOOL)  --mode=uninstall rm -f $(DESTDIR)$(toolexeclibdir)/$$p; \
	done

.c.o:
	$(COMPILE) -c $<

# FIXME: We should only use cygpath when building on Windows,
# and only if it is available.
.c.obj:
	$(COMPILE) -c `cygpath -w $<`

.s.o:
	$(COMPILE) -c $<

.S.o:
	$(COMPILE) -c $<

mostlyclean-compile:
	-rm -f *.o core *.core
	-rm -f *.$(OBJEXT)

clean-compile:

distclean-compile:
	-rm -f *.tab.c

maintainer-clean-compile:

.c.lo:
	$(LIBTOOL) --mode=compile $(COMPILE) -c $<

.S.lo:
	$(LIBTOOL) --mode=compile $(COMPILE) -c $<

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs

distclean-libtool:

maintainer-clean-libtool:

libgc.la: $(libgc_la_OBJECTS) $(libgc_la_DEPENDENCIES)
	$(LINK)  $(libgc_la_LDFLAGS) $(libgc_la_OBJECTS) $(libgc_la_LIBADD) $(LIBS)

mostlyclean-checkPROGRAMS:

clean-checkPROGRAMS:
	-test -z "$(check_PROGRAMS)" || rm -f $(check_PROGRAMS)

distclean-checkPROGRAMS:

maintainer-clean-checkPROGRAMS:

gctest$(EXEEXT): $(gctest_OBJECTS) $(gctest_DEPENDENCIES)
	@rm -f gctest$(EXEEXT)
	$(LINK) $(gctest_LDFLAGS) $(gctest_OBJECTS) $(gctest_LDADD) $(LIBS)

tags: TAGS

ID: $(HEADERS) $(SOURCES) $(LISP)
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	here=`pwd` && cd $(srcdir) \
	  && mkid -f$$here/ID $$unique $(LISP)

TAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) $(LISP)
	tags=; \
	here=`pwd`; \
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	test -z "$(ETAGS_ARGS)$$unique$(LISP)$$tags" \
	  || (cd $(srcdir) && etags $(ETAGS_ARGS) $$tags  $$unique $(LISP) -o $$here/TAGS)

mostlyclean-tags:

clean-tags:

distclean-tags:
	-rm -f TAGS ID

maintainer-clean-tags:

distdir = $(PACKAGE)-$(VERSION)
top_distdir = $(distdir)

# This target untars the dist file and tries a VPATH configuration.  Then
# it guarantees that the distribution is self-contained by making another
# tarfile.
distcheck: dist
	-rm -rf $(distdir)
	GZIP=$(GZIP_ENV) $(TAR) zxf $(distdir).tar.gz
	mkdir $(distdir)/=build
	mkdir $(distdir)/=inst
	dc_install_base=`cd $(distdir)/=inst && pwd`; \
	cd $(distdir)/=build \
	  && ../configure --srcdir=.. --prefix=$$dc_install_base \
	  && $(MAKE) $(AM_MAKEFLAGS) \
	  && $(MAKE) $(AM_MAKEFLAGS) dvi \
	  && $(MAKE) $(AM_MAKEFLAGS) check \
	  && $(MAKE) $(AM_MAKEFLAGS) install \
	  && $(MAKE) $(AM_MAKEFLAGS) installcheck \
	  && $(MAKE) $(AM_MAKEFLAGS) dist
	-rm -rf $(distdir)
	@banner="$(distdir).tar.gz is ready for distribution"; \
	dashes=`echo "$$banner" | sed s/./=/g`; \
	echo "$$dashes"; \
	echo "$$banner"; \
	echo "$$dashes"
dist: distdir
	-chmod -R a+r $(distdir)
	GZIP=$(GZIP_ENV) $(TAR) chozf $(distdir).tar.gz $(distdir)
	-rm -rf $(distdir)
dist-all: distdir
	-chmod -R a+r $(distdir)
	GZIP=$(GZIP_ENV) $(TAR) chozf $(distdir).tar.gz $(distdir)
	-rm -rf $(distdir)
distdir: $(DISTFILES)
	-rm -rf $(distdir)
	mkdir $(distdir)
	-chmod 777 $(distdir)
	@for file in $(DISTFILES); do \
	  if test -f $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    cp -pr $$d/$$file $(distdir)/$$file; \
	  else \
	    test -f $(distdir)/$$file \
	    || ln $$d/$$file $(distdir)/$$file 2> /dev/null \
	    || cp -p $$d/$$file $(distdir)/$$file || :; \
	  fi; \
	done
check-TESTS: $(TESTS)
	@failed=0; all=0; \
	srcdir=$(srcdir); export srcdir; \
	for tst in $(TESTS); do \
	  if test -f $$tst; then dir=.; \
	  else dir="$(srcdir)"; fi; \
	  if $(TESTS_ENVIRONMENT) $$dir/$$tst; then \
	    all=`expr $$all + 1`; \
	    echo "PASS: $$tst"; \
	  elif test $$? -ne 77; then \
	    all=`expr $$all + 1`; \
	    failed=`expr $$failed + 1`; \
	    echo "FAIL: $$tst"; \
	  fi; \
	done; \
	if test "$$failed" -eq 0; then \
	  banner="All $$all tests passed"; \
	else \
	  banner="$$failed of $$all tests failed"; \
	fi; \
	dashes=`echo "$$banner" | sed s/./=/g`; \
	echo "$$dashes"; \
	echo "$$banner"; \
	echo "$$dashes"; \
	test "$$failed" -eq 0
info-am:
info: info-am
dvi-am:
dvi: dvi-am
check-am: $(check_PROGRAMS)
	$(MAKE) $(AM_MAKEFLAGS) check-TESTS
check: check-am
installcheck-am:
installcheck: installcheck-am
install-info-am: 
install-info: install-info-am
install-exec-am: install-toolexeclibLTLIBRARIES
install-exec: install-exec-am

install-data-am:
install-data: install-data-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am
install: install-am
uninstall-am: uninstall-toolexeclibLTLIBRARIES
uninstall: uninstall-am
all-am: Makefile $(LTLIBRARIES)
all-redirect: all-am
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) AM_INSTALL_PROGRAM_FLAGS=-s install
installdirs:
	$(mkinstalldirs)  $(DESTDIR)$(toolexeclibdir)


mostlyclean-generic:

clean-generic:

distclean-generic:
	-rm -f Makefile $(CONFIG_CLEAN_FILES)
	-rm -f config.cache config.log stamp-h stamp-h[0-9]*

maintainer-clean-generic:
mostlyclean-am:  mostlyclean-toolexeclibLTLIBRARIES mostlyclean-compile \
		mostlyclean-libtool mostlyclean-checkPROGRAMS \
		mostlyclean-tags mostlyclean-generic

mostlyclean: mostlyclean-am

clean-am:  clean-toolexeclibLTLIBRARIES clean-compile clean-libtool \
		clean-checkPROGRAMS clean-tags clean-generic \
		mostlyclean-am

clean: clean-am

distclean-am:  distclean-toolexeclibLTLIBRARIES distclean-compile \
		distclean-libtool distclean-checkPROGRAMS \
		distclean-tags distclean-generic clean-am
	-rm -f libtool

distclean: distclean-am
	-rm -f config.status

maintainer-clean-am:  maintainer-clean-toolexeclibLTLIBRARIES \
		maintainer-clean-compile maintainer-clean-libtool \
		maintainer-clean-checkPROGRAMS maintainer-clean-tags \
		maintainer-clean-generic distclean-am
	@echo "This command is intended for maintainers to use;"
	@echo "it deletes files that may require special tools to rebuild."

maintainer-clean: maintainer-clean-am
	-rm -f config.status

.PHONY: mostlyclean-toolexeclibLTLIBRARIES \
distclean-toolexeclibLTLIBRARIES clean-toolexeclibLTLIBRARIES \
maintainer-clean-toolexeclibLTLIBRARIES \
uninstall-toolexeclibLTLIBRARIES install-toolexeclibLTLIBRARIES \
mostlyclean-compile distclean-compile clean-compile \
maintainer-clean-compile mostlyclean-libtool distclean-libtool \
clean-libtool maintainer-clean-libtool mostlyclean-checkPROGRAMS \
distclean-checkPROGRAMS clean-checkPROGRAMS \
maintainer-clean-checkPROGRAMS tags mostlyclean-tags distclean-tags \
clean-tags maintainer-clean-tags distdir check-TESTS info-am info \
dvi-am dvi check check-am installcheck-am installcheck install-info-am \
install-info install-exec-am install-exec install-data-am install-data \
install-am install uninstall-am uninstall all-redirect all-am all \
installdirs mostlyclean-generic distclean-generic clean-generic \
maintainer-clean-generic clean mostlyclean distclean maintainer-clean

# The following hack produces a warning from automake, but we need it in order 
# to build a file from a subdirectory. FIXME.
test.o:	tests/test.c
	$(COMPILE) -c tests/test.c
$(all_objs) : include/private/gcconfig.h include/private/gc_priv.h \
include/private/gc_hdrs.h include/gc.h include/gc_gcj.h include/gc_mark.h

.s.lo:
	$(LTCOMPILE) -Wp,-P -x assembler-with-cpp -c $<

# Multilib support.
.PHONY: all-multi mostlyclean-multi clean-multi distclean-multi \
	maintainer-clean-multi

all-am: all-multi
install-am: install-multi
mostlyclean-am: mostlyclean-multi
clean-am: clean-multi
distclean-am: distclean-multi
maintainer-clean-am: maintainer-clean-multi

all-multi:
	$(MULTIDO) $(AM_MAKEFLAGS) DO=all multi-do
install-multi:
	$(MULTIDO) $(AM_MAKEFLAGS) DO=install multi-do
mostlyclean-multi:
	$(MULTICLEAN) $(AM_MAKEFLAGS) DO=mostlyclean multi-clean
clean-multi:
	$(MULTICLEAN) $(AM_MAKEFLAGS) DO=clean multi-clean
distclean-multi:
	$(MULTICLEAN) $(AM_MAKEFLAGS) DO=distclean multi-clean
maintainer-clean-multi:
	$(MULTICLEAN) $(AM_MAKEFLAGS) DO=maintainer-clean multi-clean

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
