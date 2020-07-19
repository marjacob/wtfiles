Windows Terminal Settings
=========================

Installation
------------

Close all instances of Windows Terminal and open `cmd.exe` (no, not through
Windows Terminal). Proceed to navigate into the ridiculous configuration
directory.

```console
cd "%LocalAppData%\Packages\MI0AEA~1.WIN\LOCALS~1"
```

Delete anything you can find in this directory, just nuke the whole damn
thing to oblivion. Now clone the repository using HTTPS or SSH into the
current directory. **Do not omit the trailing dot.**

```console
git clone git@github.com:marjacob/wtfiles.git .
```

or

```console
git clone https://github.com/marjacob/wtfiles.git .
```

Now open Windows Terminal. From now and into the sunset, changes to the
configuration file will be picked up and reflected automatically.
