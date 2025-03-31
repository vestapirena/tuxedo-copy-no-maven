@echo off
REM Start Tuxedo domain
set TUXCONFIG=C:\tuxedo\config\tuxconfig
set APPDIR=C:\tuxedo\apps
call %TUXDIR%\bin\tlisten -m
call %TUXDIR%\bin\tmboot -y
