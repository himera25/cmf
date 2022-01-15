Repository needs to be in folder D:\\_CMFCosmopolitan

For developers who arent using VS code assets build script is in assets folder ( D:\_CMFCosmopolitan\CMF_FrontEnd\Modular.WebHost\assets )  - build_assets.bat

Project alse requires core ( https://bitbucket.org/Wireless_Media/origami-cms-core-templates-prototype ) that needs to be in D:_CMFCosmopolitan\CMF_FrontEnd\Modular.WebHost\assets\core

Task for building core assets is also in assets folder - build_assets_core.bat

For developers who arent using VS code cmf build script is in Modular.WebHost folder - build_cmf.bat

In C partition create folder CMFTools and put inside MSBuild.exe and nuget.exe.

MSBuild.exe can be found in C:\Windows\Microsoft.NET\Framework64\v4.0.30319

Nuget.exe can be downloaded from https://www.nuget.org/downloads