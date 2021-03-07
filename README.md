# Daffodil
Daffodil provides native multi-targeting platform toolsets for Visual 
Studio 2010 C++ developers who need to target older versions of Visual 
Studio. Forked from https://daffodil.codeplex.com/

To use these platform toolsets, you must have the targeted version of 
Visual Studio installed. Currently supported platforms are:
- Visual Studio 2005 (VC 8)
- Visual Studio 2003 (VC 7.1)
- Visual Studio 2002 (VC 7)
- Visual Studio 6 (VC 6)

## Visual Studio 2012 or later versions
Daffodil works fine in Visual Studio 2012 and later versions because these versions can use toolsets found within Visual Studio 2010's MSBuild.
As long as Visual Studio 2010 is installed, run Daffodil.ENU.msi to install these platform toolsets.

It is possible to port the toolsets to specific version of Visual Studio so that Visual Studio 2010 is not required.
As an example, a port for Visual Studio 2015 is provided through Daffodil_vs2015.ENU.msi.

## Additional Information
http://web.archive.org/web/20120910065925/http://blogs.msdn.com/b/vcblog/archive/2009/12/08/c-native-multi-targeting.aspx?PageIndex=1
http://otb.manusoft.com/2010/10/visual-studio-2010-native-multi-targeting.htm
