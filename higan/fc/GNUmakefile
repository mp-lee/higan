processors += mos6502

objects += fc-interface fc-system fc-controller
objects += fc-memory fc-cartridge fc-cpu fc-apu fc-ppu

obj/fc-interface.o:  fc/interface/interface.cpp $(call rwildcard,fc/interface/)
obj/fc-system.o:     fc/system/system.cpp $(call rwildcard,fc/system/)
obj/fc-controller.o: fc/controller/controller.cpp $(call rwildcard,fc/controller/)
obj/fc-memory.o:     fc/memory/memory.cpp $(call rwildcard,fc/memory/)
obj/fc-cartridge.o:  fc/cartridge/cartridge.cpp $(call rwildcard,fc/cartridge/)
obj/fc-cpu.o:        fc/cpu/cpu.cpp $(call rwildcard,fc/cpu/)
obj/fc-apu.o:        fc/apu/apu.cpp $(call rwildcard,fc/apu/)
obj/fc-ppu.o:        fc/ppu/ppu.cpp $(call rwildcard,fc/ppu/)
