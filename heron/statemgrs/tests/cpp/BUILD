package(default_visibility = ["//visibility:public"])

cc_test(
    name = "zk-statemgr_unittest",
    srcs = [
        "zkstatemgr_unittest.cpp",
    ],
    deps = [
        "//heron/statemgrs/src/cpp:statemgrs-cxx",
        "//3rdparty/gmock:gmock-cxx",
        "//3rdparty/gtest:gtest-cxx",
    ],
    copts = [
        "-Iheron",
        "-Iheron/common/src/cpp",
        "-Iheron/statemgrs/src/cpp",
        "-I$(GENDIR)/heron",
        "-I$(GENDIR)/heron/common/src/cpp",
    ],
    size = "small",
    linkstatic = 1,
)
