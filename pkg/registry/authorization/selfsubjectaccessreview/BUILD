package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = ["rest.go"],
    tags = ["automanaged"],
    deps = [
        "//pkg/api:go_default_library",
        "//pkg/api/errors:go_default_library",
        "//pkg/apis/authorization:go_default_library",
        "//pkg/apis/authorization/validation:go_default_library",
        "//pkg/auth/authorizer:go_default_library",
        "//pkg/registry/authorization/util:go_default_library",
        "//pkg/runtime:go_default_library",
    ],
)
