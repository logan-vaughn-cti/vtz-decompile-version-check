# VTZ Decompiler version check

This repo holds one file, `version.json`, which CTI's VTZ Decompiler reads at start-up to learn whether a newer version exists. The program itself, its source and its setup live in Azure DevOps (CTI-AV / Skunkworks / VTZ-Decompiler); `url` is where the program's Download button sends people. Update `version` only after the new setup is merged to `main` there. The rules for the file are in that repo's README, under *Releasing a version*.
