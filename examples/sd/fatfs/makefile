# Copyright 2012 Olivier Gillet.
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <http://www.gnu.org/licenses/>.

F_CPU          = 32000000
# MCU_NAME       = 32a4
MCU_NAME       = 128a3
TARGET         = fatfs_reader
PACKAGES       = avrlibx \
		avrlibx/filesystem \
		avrlibx/system \
		avrlibx/third_party/ff \
		examples/sd/fatfs
MMC_CONFIG     = \
		-DMMC_CS_PORT=D \
		-DMMC_CS_BIT=4 \
		-DMMC_SPI_PORT=D

include avrlibx/makefile.mk
