cmake_minimum_required(VERSION 3.0.0)
project(libspnav VERSION 0.1.0)

aux_source_directory(. DIR_SRCS)

set(header ${DIR_SRCS}/spnav.h
${DIR_SRCS}/spnav_config.h
${DIR_SRCS}/spnav_magellan.h)

add_library(spnav SHARED ${DIR_SRCS})







