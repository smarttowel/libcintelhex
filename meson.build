project('libcintelhex', 'c',
    version: '1.0.0',
    default_options : ['warning_level=2', 
                       'cpp_std=c++17',
                       'prefix=/usr'])

libcintelhex_lib = static_library('libcintelhex',
                                  'src/ihex_parse.c',
                                   include_directories: include_directories('include'))
libcintelhex_dep = declare_dependency(link_with: libcintelhex_lib,
                                      include_directories: include_directories('include'))
