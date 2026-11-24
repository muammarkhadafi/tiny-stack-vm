# tiny-stack-vm

A tiny stack virtual machine for the make.fun bounty [tiny-stack-vm-01-run-20261122](https://make.fun/bounty/tiny-stack-vm-01-run-20261122).

[![make.fun](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/muammarkhadafi/tiny-stack-vm/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/muammarkhadafi/tiny-stack-vm/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)

`main.ts` runs make.fun's tiny stack ISA. For each of 40 instances it reads `/input/<id>/program.bin` and `input.bin`, then writes `/output/<id>/stdout.bin` and `exit.txt`. It scores 1,000,000 on the practice set.

Built as a single golfed file (2,897 bytes). Verified against the kit's reference VM: 40/40 practice instances at a perfect score, 300 random programs with zero mismatches, and byte-identical output across repeated runs.
