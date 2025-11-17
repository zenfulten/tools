## Changelog v1.4.4

References | Description | Author(s)
--- | --- | ---
#1185 | Fix auto-detection of CPU temp on Ampere boards | @bexcran
589c133 | Fixed floating_humanizer() to work correctly when numeric delimiter isn't a dot. | @aristocratos
#1157 | Add command line option to set an inital filter | @imwints
#1172 | Make 100ms the minimal refresh rate. Exit gracefully if integer conversion in CLI parser fails. | @imwints
#1031 | Lock/unlock config to avoid infinite recursion | @Jacajack
#1156 | Fix incorrect positioning and start symbol of second title introduced in 2538d89 | @xDMPx
ffcd064 | Fix dangling reference warnings for GCC 13 and later | aristocratos

Big thanks to @imwints for helping out with project maintenance, PR reviews and merging!

**For additional binaries see the [Continuous Builds](https://github.com/aristocratos/btop/actions).**

**Linux binaries for each architecture are statically linked with musl and works on kernel 2.6.39 and newer.**

**No MacOs or BSD binaries provided for the moment.**

**Notice! None of the binaries have GPU support, compile yourself or wait for distribution packages for GPU monitoring support!**

**Notice! Use x86_64 for 64-bit x86 systems, i486 and i686 are 32-bit!**
