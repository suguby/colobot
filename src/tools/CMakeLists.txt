set(CONVERT_MODEL_SOURCES
../common/iman.cpp
../common/logger.cpp
../common/stringutils.cpp
../graphics/engine/modelfile.cpp
convert_model.cpp
)

include_directories(. ..)

add_definitions(-DMODELFILE_NO_ENGINE)

add_executable(convert_model ${CONVERT_MODEL_SOURCES})
