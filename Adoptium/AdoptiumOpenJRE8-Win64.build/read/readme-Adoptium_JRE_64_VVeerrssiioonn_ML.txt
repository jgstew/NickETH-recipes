Adoptium Open JRE x64 8.0.100 ML (Multi-Language)
Java Runtime Environment for x64 Windows.
Adoptium is the successor of AdoptOpenJDK.
1:1 substitution for Oracle JavaRE

Tested on Windows 7, 8.1 + 10

Optional features:
FeatureEnvironment	Add to PATH environment variable.
FeatureIcedTeaWeb	Install the IcedTea-Web package
::	FeatureJNLPFileRunWith	Associate .jnlp files to run with IcedTea-Web
::	FeatureJarFileRunWith	Associate .jar files to run with AdoptOpenJDK
FeatureJavaFX		Install JavaFX
FeatureJavaHome		Set JAVA_HOME environment variable.
FeatureOracleJavaSoft	JavaSoft (Oracle) registry keys	Overwrites the reg keys HKLM\Software\JavaSoft (Oracle).
To install an additional feature, add ADDLOCAL=feature1,feature2...

To install all features to a machine, use this command:
msiexec /i "Adoptium_JRE_Hotspot_64_8.0.100.0_ML.msi" ALLUSERS=1 ADDLOCAL=ALL

Slient Install: msiexec /i "Adoptium_JRE_Hotspot_64_8.0.100.0_ML.msi" /qn (absolute silent) or /qb! (with progress-dialog).

All MSI-versions from Adopt are found and automatically removed. Only one version can be installed.

Features in this version:
- Multi-Language enu, deu, fra.
- Webstart.
- JavaFX support.

Release 1.0, Build 1
20191115, Nick Heim
