# Malwear-Sweet

* SilenBishop

	Reimplementation of b33f's UrbanBishop with syscall
	
* BootExecuteNativeApp

	Native application for BootExecute/SetupExecute key persistence test. No MSVCRT, soley rely on ntdll.dll. Clone the repo. add the project by "Open a project or solution", and select the `.vcxproj` file.

	References:
	<br/>&emsp;&emsp;https://renenyffenegger.ch/notes/Windows/development/native-applications/index
	<br/>&emsp;&emsp;https://stackoverflow.com/questions/10164724/windows-registry-how-to-add-your-native-program-for-boot-executing

* TheLostThread

    Hijack a thread without calling SetThreadContext. Still needs improvement because I'm lazy and haven't implement the whole thing well enough to maintain the original functionality of the thread. Just a quick and dirty PoC.

# Credit

* [FuzzySecurity/Sharp-Suite](https://github.com/FuzzySecurity/Sharp-Suite/blob/master/UrbanBishop/UrbanBishop.sln) @b33f
* MalDevAcademy @mrd0x @NUL0x4C
