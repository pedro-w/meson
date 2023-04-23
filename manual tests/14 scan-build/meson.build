project('PCHTest', 'c', version: '1.0')

# Configure with Ninja back-end
#   meson setup . builddir
# compile with
#   ninja -C builddir scan-build

executable('hello', 
  sources: ['main.c'], 
  c_pch: 'pch/hello-pch.h')
