<h1 align="center">WordPress Crack<br/>Super Fast Login</h1>

> Update from version 1.1 to version 1.2

```
WordPress Brute Force Fast Login
Author : RandsX@22XploiterCrew
E-Mail : dev@22xploitercrew.my.id

usage: python3 wp-crack.py url username [-p|-P] [-x PROXY] [-v VERBOSE]
                                                                positional arguments:
  url               url the target
  username          username target

optional arguments:
  -h, --help        show this help message and exit
  -V, --version     show program's version number and exit
  -v, --verbose     verbose mode/show username and password
                    combination for each attempt
  -p , --password   use one word password
  -P , --passlist   use a few words password
  -x , --proxy      use a socks/proxy for request (ex:
                    127.0.0.1:8080)

Please check your target first so that the login process runs
smoothly
```

## What's new?
- Fixed bugs
- Added a socks/proxy feature for requests
- Using the new module ```requests``` and ```colorama```
- Easy to use
- Multiprocessing

## How to use
The super fast login feature is only available if you guess (brute force) the target using a wordlist password.
- Single brute
```bash
python3 wp-crack https://site.com username -p password
```

- Mass brute
```bash
python3 wp-crack https://site.com username -P password.txt
```

if you wish to display the password and username that was attempted to enter into the target, use option ```-v/--verbose```