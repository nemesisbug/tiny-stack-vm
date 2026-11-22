# tiny-stack-vm

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/nemesisbug/tiny-stack-vm/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/nemesisbug/tiny-stack-vm/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

A tiny stack virtual machine for make.fun's tiny-stack-vm-01-run-20261122 bounty: one program answers all 40 instances of the tiny stack ISA (32-bit wrapping integers, 256-value stack, calls, 256 words of memory, ten traps with their own exit codes). Byte-faithful to the kit's reference VM, compacted for the size tie-break. Run with `node main.ts /input /output` (Node 22, no dependencies): reads `/input/<id>/program.bin` + `input.bin`, writes `/output/<id>/stdout.bin` + `exit.txt` for `i001`–`i040`.
