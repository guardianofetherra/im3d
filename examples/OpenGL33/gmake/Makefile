# GNU Make workspace makefile autogenerated by Premake

ifndef config
  config=debug_win32
endif

ifndef verbose
  SILENT = @
endif

ifeq ($(config),debug_win32)
  im3d_opengl33_config = debug_win32
endif
ifeq ($(config),debug_win64)
  im3d_opengl33_config = debug_win64
endif
ifeq ($(config),release_win32)
  im3d_opengl33_config = release_win32
endif
ifeq ($(config),release_win64)
  im3d_opengl33_config = release_win64
endif

PROJECTS := im3d_opengl33

.PHONY: all clean help $(PROJECTS) 

all: $(PROJECTS)

im3d_opengl33:
ifneq (,$(im3d_opengl33_config))
	@echo "==== Building im3d_opengl33 ($(im3d_opengl33_config)) ===="
	@${MAKE} --no-print-directory -C . -f im3d_opengl33.make config=$(im3d_opengl33_config)
endif

clean:
	@${MAKE} --no-print-directory -C . -f im3d_opengl33.make clean

help:
	@echo "Usage: make [config=name] [target]"
	@echo ""
	@echo "CONFIGURATIONS:"
	@echo "  debug_win32"
	@echo "  debug_win64"
	@echo "  release_win32"
	@echo "  release_win64"
	@echo ""
	@echo "TARGETS:"
	@echo "   all (default)"
	@echo "   clean"
	@echo "   im3d_opengl33"
	@echo ""
	@echo "For more information, see https://github.com/premake/premake-core/wiki"