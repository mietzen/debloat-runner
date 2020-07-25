## This script frees up GitHub runner diskspace, leaving you with an delboated runner (with docker).

Initial: 
```
Filesystem      Size  Used Avail Use% Mounted on
/dev/sdb1        84G   55G   29G  66% /
```

After Free-Up:
```
Filesystem      Size  Used Avail Use% Mounted on
/dev/sdb1        84G   11G   73G  13% /
```

There is some potainial left (`/usr` is still a bit bloated), but this was good enough for my use case.
