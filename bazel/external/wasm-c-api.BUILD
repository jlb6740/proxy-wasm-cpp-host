load("@rules_cc//cc:defs.bzl", "cc_library")

licenses(["notice"])  # Apache 2

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "wasmtime_lib",
    hdrs = [
        "include/wasm.h",
    ],
    include_prefix = "wasmtime",
    deps = [
        #"@com_github_bytecodealliance_wasmtime//:rust_c_api",
        "@com_github_jlb6740_wasmtime//:rust_c_api",
    ],
)
