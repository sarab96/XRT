# SPDX-License-Identifier: Apache-2.0
# Copyright (C) 2019-2021 Xilinx, Inc. All rights reserved.
#
set(XRT_WINDOWS_HEADER_SRC
  types.h
  uuid.h)

install (FILES ${XRT_WINDOWS_HEADER_SRC} DESTINATION ${XRT_INSTALL_DIR}/include/windows)

message("-- XRT OS native header files")
foreach (header ${XRT_WINDOWS_HEADER_SRC})
  message("-- ${header}")
endforeach()
