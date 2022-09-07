# windows-scheduler-sample
bat script to schedule any executable script on windows platform

* Edit script and edit the template top execute the required script
* to test ./python-scheduler (can be renamed as well) (scope to enhance as well)

```
@echo off
for %%x in (
<<<option1>>>          <<<<<add option here
<<<option2>>>>
) do (
 echo "%%x"
 echo "C:\Python38\python.exe" "C:\<PATH_TO_EXECUTABLE> - %%x"     <<add path here
 echo =-=-=-=-=-=
 echo.
)
```
