workspace(name = "com_google_jsinterop_generator")

maven_server(
    name = "sonatype_snapshot",
    url = "https://oss.sonatype.org/content/repositories/snapshots",
)

maven_jar(
    name = "jsr305",
    artifact = "com.google.code.findbugs:jsr305:3.0.1",
)

maven_jar(
    name = "guava",
    artifact = "com.google.guava:guava:21.0",
)

maven_jar(
    name = "args4j",
    artifact = "args4j:args4j:2.33",
)

maven_jar(
    name = "auto_value",
    artifact = "com.google.auto.value:auto-value:1.4",
)

maven_jar(
    name = "jscomp",
    artifact = "com.google.javascript:closure-compiler:1.0-SNAPSHOT",
    server = "sonatype_snapshot",
)

maven_jar(
    name = "jsinterop_annotations",
    artifact = "com.google.jsinterop:jsinterop-annotations:1.0.2",
)

maven_jar(
    name = "error_prone",
    artifact = "com.google.errorprone:error_prone_annotations:2.0.19",
)

new_http_archive(
  name="com_google_closure_compiler",
  url="https://github.com/google/closure-compiler/archive/v20170409.tar.gz",
  build_file="jscomp.BUILD",
  strip_prefix="closure-compiler-20170409"
)

http_jar(
    name = "com_google_google_java_format",
    url = "https://github.com/google/google-java-format/releases/download/google-java-format-1.3/google-java-format-1.3-all-deps.jar",
)

maven_jar(
    name = "com_google_jsinterop_base",
    artifact = "com.google.jsinterop:base:1.0.0-RC1",
)