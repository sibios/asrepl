AC_PREREQ([2.69])
AC_INIT([asrepl], [0.1])
AC_CONFIG_SRCDIR([asrepl.c])
AC_CONFIG_FILES([Makefile])
AC_CONFIG_HEADER([config.h])
AC_LANG_C

# Checks for programs.
AC_PROG_CC

# Definitions
# AC_DEFINE([ASSEMBLER], CCAS, [Define assembler to use.])

# Checks for libraries.
AC_CHECK_LIB([readline], [readline])
AC_CHECK_LIB([keystone], [ks_asm])
AC_CHECK_LIB([unicorn], [uc_version])

# Checks for header files.
AC_CHECK_HEADERS([stdint.h stdlib.h string.h unistd.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_HEADER_STDBOOL
AC_TYPE_PID_T
AC_TYPE_SIZE_T
AC_TYPE_UINT8_T

# Checks for library functions.
AC_FUNC_FORK
AC_FUNC_MALLOC
AC_CHECK_FUNCS([memset strerror])

AC_OUTPUT
