set (Boxes_SRC 
	${CMAKE_CURRENT_SOURCE_DIR}/CMakeLists.txt
	${CMAKE_CURRENT_SOURCE_DIR}/Boxes.cl
	${CMAKE_CURRENT_SOURCE_DIR}/Boxes.h
	${CMAKE_CURRENT_SOURCE_DIR}/Boxes.hpp
	${CMAKE_CURRENT_SOURCE_DIR}/Boxes.cpp
	PARENT_SCOPE)

set (Boxes_KRNL
	#${CMAKE_CURRENT_SOURCE_DIR}/Boxes.h
	${CMAKE_CURRENT_SOURCE_DIR}/Boxes.cl
	PARENT_SCOPE)