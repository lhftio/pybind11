package(default_visibility = ["//visibility:public"])

cc_library(
    name = "pybind11",
    deps = [
        "@python//:headers",
    ],
    includes = [
        "include",
    ],
    hdrs = glob([
        "include/**/*.h",
    ]),
)
