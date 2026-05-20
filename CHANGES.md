# Goo Pumps & Oils' Speed Pump :: Changes

* 2026-0520: 1.9.1.3 (LisiasT) for KSP >= 1.3.1
	+ I think I finally detected the problem - DLL file permissions.
		- DLLs without write permissions are not loaded, at least on MacOS (and I'm betting on Linux too).
		- Rant: ***JESUS FSCKING CHRIST***, Unity/KSP (I don't know which one, to tell the truth) don't waste a single opportunity to go to that extra mile to be absolutely sure your rig is insecure. **DAMNIT**.
* 2026-0325: 1.9.1.2 (LisiasT) for KSP >= 1.3.1
	+ Something gone South last release. Dunno why, but rebuilding everything fixed the issue.
		- ~~I must had messed up some building script, I think...~~ (Found the reason, I messed up the dependecy thingy).
	+ Russian localization.
		- Thanks [BezKartuza](https://forum.kerbalspaceprogram.com/profile/200469-bezkartuza/)!
	+ Updates `KSPe.Light` to 2.5.5.2, fixing a lame mistake that prevented it from working on KSP < 1.8.0 🤦
* 2026-0322: 1.9.1.1 (LisiasT) for KSP >= 1.3.1
	+ ***DITCHED*** due a botched building.
* 2023-0610: 1.9.1.0 (LisiasT) for KSP >= 1.3.1
	+ Adds `ja` Localization
* 2023-0129: 1.9.0.11 (LisiasT) for KSP >= 1.3.1
	+ Adds `it-it` Localization
	+ Updates `KSPe.Light` to latest version
* 2022-1114: 1.9.0.10 (LisiasT) for KSP >= 1.3.1
	+ Adds `es-es` Localization
	+ Minor code compliance changes.
	+ Updates `KSPe.Light` to latest version
* 2022-0917: 1.9.0.9 (LisiasT) for KSP >= 1.3.1
	+ Adds `pt-br` Localization
	+ Prevents pumping resources not meant to be transferrable
	+ Closes issues:
		- [#28](https://github.com/net-lisias-ksp/GPOSpeedPump/issues/28) GPOSP is trying to pump non pumpeable resources!
		- [#25](https://github.com/net-lisias-ksp/GPOSpeedPump/issues/25) Brazilian Portuguese (Português Brasil) \<pt-br.cfg\>
* 2022-0916: 1.9.0.8 (LisiasT) for KSP >= 1.3.1
	+ ***DITCHED*** due a major but small mistake on setting the pumps!
		- Yep, I had one of **that** weeks... 
* 2022-0916: 1.9.0.7 (LisiasT) for KSP >= 1.3.1
	+ ***DITCHED*** due major U.I. flaw due some still unknown idiossyncrasy on KSP.
		- See [Issue #29](https://github.com/net-lisias-ksp/GPOSpeedPump/issues/29) for details.
* 2022-0915: 1.9.0.6 (LisiasT) for KSP >= 1.3.1
	+ Fix a lame mistake on the dependency checking
	+ Implements Localization for the EN-US language
		- More to come! 
* 2022-0421: 1.9.0.5 (LisiasT) for KSP >= 1.3.1
	+ A pretty lame mistake was detected and fixed.
	+ Closes issues:
		+ [#2](https://github.com/net-lisias-ksp/GPOSpeedPump/issues/2) NRE on Balance  	
* 2022-0418: 1.9.0.4 (LisiasT) for KSP >= 1.3.1
	+ Some naming problems that passed trough last release was fixed.
	+ Added a "Migration" tool to preserve crafts and games migrating from the previous `GPOSpeedFuelPump` releases.
	+ Implements the KSPe's new Compatibility Checks. 
* 2022-0415: 1.9.0.3 (LisiasT) for KSP >= 1.3.1
	+ Officially naming the thing to `GPOSpeedPump` / `Goo Pumps & Oils' Speed Pump`
	+ Added 3rd Party Support by zer0Kerbal.
	+ Moving from `KSPe` to `KSPe.Light`.
	+ Proceeding into adopting it on Forum.
* 2022-0403: 1.9.0.1 (LisiasT) for KSP >= 1.3.1
	+ Adds KSPe facilities:
		- Logs
		- Installment checks
		- Abstracted GUI/GUILayout support
	+ Certifies the thing to work up to KSP 1.12.3 :)
	+ Certifies the thing to work down to KSP 1.3.1 
	+ Adds (experimental) support for Simple Fuel Switch.
* 2022-0403: 1.9.0.0 (LisiasT) for KSP >= 1.3.1
	+ Ditched as a new release was made in less than 24 hours.
