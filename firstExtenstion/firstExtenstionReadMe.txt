How to write and install extension?

1) create a folder named "it_can_be_any_name ;)"
2) create a file named "manifest" and save it as "json" type (2.1,2.2)
3) Manifest is a case sensitive(3.1)
4) insert "chrome://extensions" in the address bar or
	go to the chrome menu -> more tools -> extensions
5) enable developers option in the right corner of the chrome
6) Click on "Load unpacked" and browse to your "it_can_be_any_name" folder
7) You won't see any json file there, only your folder

COMMON MISTAKES &  SOLUTION
2.1) I created a file "manifest.json" as set type as "json" which doesn't work.
2.2) So I renamed it with "manifest" and kept the type same as before.
3.1) I wrote "manifest-version" instead of "manifest_version"