This is a combination of kexts, DSDT/SSDT and config.plist for Clover that I use to run macOS on my VAIO VPCCA3S1R laptop.
What is currently not working:
- brightness controls (has something to do with DSDT or SSDT, probably)
- card reader (i don't use it and thereby did not search for a specific kext)
- AppleHDA (VoodooHDA is included)
- camera, sometimes

What is working:
- everyhing else

Changes:
- radeon card was turned off in SSDT
- an AR9287 adapter was bought for 100 RUR in order to make Wi-Fi work (standard AR9485 is incompatible)

Limitations:
- if you use an adapter other than a compatible Atheros one then remove toledaARPT.kext
- do not use macOS Sierra 10.12, FN keys are not working. Use 10.12.1 or higher version.
