# go-hd-naumen
Go - Functions to work with HD Naumen API

Functions:
* GetServiceCall - Get ServiceCall and task id(RP) based on data parameter(GET).
* GetTaskSumDescriptionAndRP - Get Request details based on serviceCall('sumDescription' filed and 'title' fielde(RP number))(GET)
* TakeSCResponsibility - Take responsibility on Naumen ticket(GET)
* AttachFilesAndSetAcceptance - Attach list of files to Naumen task and set 'ready for acceptance'(POST)

<h3>json example of naumen data</h3>

```
{
    "naumen-base-url": "https://YOUR-NAUMEN-BASE-URL",
    "naumen-access-key": "YOUR NAUMEN API ACCESS KEY"
}
```