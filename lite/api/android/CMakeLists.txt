if ((NOT LITE_WITH_JAVA) OR (NOT LITE_WITH_ARM) OR (NOT LITE_WITH_CSKY))
  return()
endif()

add_subdirectory(jni)
