Renamer.Net
====

.Net assembly renamer

Commandline Options
----
* __-s / --src__
  변경할 파일들의 목록
* __-d / --dst__
  저장할 경로의 목록
* __-f / --from__
  검색할 네임스페이스 이름
* __-t / __to__
  변경할 네임스페이스 이름
* r / --recursive
  해당 어셈블리의 참조까지 모두 변경합니다. (not implemented yet)
* g / regex
  `from` 옵션의 값이 정규식임을 지정합니다.
(bold -> mandatory option)

Example
----
```
renamer -s testdll.dll -d output.dll -f JinwooDoo -t MyDll
```
![example](img/example.png)


Download
----
[GithubReleasePage]()