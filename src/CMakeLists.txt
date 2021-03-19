tnt_project_AddLibrary(${PROJECT_NAME}
  TARGET
    ${PROJECT_NAME}
  SOURCES
    sandbox.cpp
)

target_compile_features(${PROJECT_NAME} PUBLIC cxx_std_17)