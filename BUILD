java_runtime(
  name = "jdk",
  java_home = "$(JAVA_HOME)",
)

java_binary(
  name = "jbox",
  srcs = glob(["src/main/java/id/jbox/*.java"]),
  deps = [
    "@maven//:com_beust_jcommander",
  ],
  main_class = "id.jbox.Main",
)
