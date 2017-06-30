licenses(['notice'])
package(default_visibility = ['//visibility:public'])

cc_test(
    name = 'test_icu',
    srcs = [
        'test_icu.cpp',
    ],
    deps = [
        '//third_party/icu4c:icu',
    ],
    linkstatic = 1,
)

cc_test(
    name = 'test_UnicodeString',
    srcs = [
        'gtest_UnicodeString.cpp',
    ],
    deps = [
        '//third_party/gflags:gflags',
        '//third_party/gtest:gtest_main',
        '//third_party/icu4c:icu',
    ],
    linkstatic = 1,
)
