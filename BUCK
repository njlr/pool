include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'boost-pool', 
  header_only = True,
  header_namespace = 'boost/pool',
  exported_headers = subdir_glob([
    ('include/boost/pool', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
