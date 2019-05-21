# Credits, Notes, Reference




```sh
(utils-import-env)  --->> pip install -r requirements.txt
Collecting git+https://github.com/s2t2/python-utils.git (from -r requirements.txt (line 2))
  Cloning https://github.com/s2t2/python-utils.git to /private/var/folders/mz/hvngrdl93zvcjxv3bxk2z7t80000gn/T/pip-req-build-o8s81mpm
  Running command git clone -q https://github.com/s2t2/python-utils.git /private/var/folders/mz/hvngrdl93zvcjxv3bxk2z7t80000gn/T/pip-req-build-o8s81mpm
    ERROR: Complete output from command python setup.py egg_info:
    ERROR: Traceback (most recent call last):
      File "<string>", line 1, in <module>
      File "/anaconda3/envs/utils-import-env/lib/python3.7/tokenize.py", line 447, in open
        buffer = _builtin_open(filename, 'rb')
    FileNotFoundError: [Errno 2] No such file or directory: '/private/var/folders/mz/hvngrdl93zvcjxv3bxk2z7t80000gn/T/pip-req-build-o8s81mpm/setup.py'
    ----------------------------------------
ERROR: Command "python setup.py egg_info" failed with error code 1 in /private/var/folders/mz/hvngrdl93zvcjxv3bxk2z7t80000gn/T/pip-req-build-o8s81mpm/
```



```sh
(utils-import-env)  --->> pip install -r requirements.txt
Collecting git+https://github.com/s2t2/python-utils.git (from -r requirements.txt (line 2))
  Cloning https://github.com/s2t2/python-utils.git to /private/var/folders/mz/hvngrdl93zvcjxv3bxk2z7t80000gn/T/pip-req-build-itz19gka
  Running command git clone -q https://github.com/s2t2/python-utils.git /private/var/folders/mz/hvngrdl93zvcjxv3bxk2z7t80000gn/T/pip-req-build-itz19gka
ERROR: Files/directories not found in /private/var/folders/mz/hvngrdl93zvcjxv3bxk2z7t80000gn/T/pip-req-build-itz19gka/pip-egg-info
```


  + https://medium.freecodecamp.org/how-to-use-github-as-a-pypi-server-1c3b0d07db2
  + https://github.com/ceddlyburge/python_world/blob/master/setup.py
  + https://stackoverflow.com/a/8256424/670433
  + https://pip.pypa.io/en/stable/reference/pip_install/#vcs-support
  + https://docs.python.org/3/distutils/setupscript.html
  + https://the-hitchhikers-guide-to-packaging.readthedocs.io/en/latest/quickstart.html

``sh
(utils-import-env)  --->> pip install -r requirements.txt
Collecting git+https://github.com/s2t2/python-utils.git (from -r requirements.txt (line 2))
  Cloning https://github.com/s2t2/python-utils.git to /private/var/folders/mz/hvngrdl93zvcjxv3bxk2z7t80000gn/T/pip-req-build-ms6__jf6
  Running command git clone -q https://github.com/s2t2/python-utils.git /private/var/folders/mz/hvngrdl93zvcjxv3bxk2z7t80000gn/T/pip-req-build-ms6__jf6
    ERROR: Complete output from command python setup.py egg_info:
    ERROR: running egg_info
    creating pip-egg-info/MyUtils.egg-info
    writing pip-egg-info/MyUtils.egg-info/PKG-INFO
    writing dependency_links to pip-egg-info/MyUtils.egg-info/dependency_links.txt
    writing top-level names to pip-egg-info/MyUtils.egg-info/top_level.txt
    writing manifest file 'pip-egg-info/MyUtils.egg-info/SOURCES.txt'
    error: package directory 'distutils' does not exist
    ----------------------------------------
ERROR: Command "python setup.py egg_info" failed with error code 1 in /private/var/folders/mz/hvngrdl93zvcjxv3bxk2z7t80000gn/T/pip-req-build-ms6__jf6/
```

```sh
(utils-import-env)  --->> pip install -r requirements.txt
Collecting git+https://github.com/s2t2/python-utils.git (from -r requirements.txt (line 2))
  Cloning https://github.com/s2t2/python-utils.git to /private/var/folders/mz/hvngrdl93zvcjxv3bxk2z7t80000gn/T/pip-req-build-oiwltx6j
  Running command git clone -q https://github.com/s2t2/python-utils.git /private/var/folders/mz/hvngrdl93zvcjxv3bxk2z7t80000gn/T/pip-req-build-oiwltx6j
    ERROR: Complete output from command python setup.py egg_info:
    ERROR: running egg_info
    creating pip-egg-info/MyUtils.egg-info
    writing pip-egg-info/MyUtils.egg-info/PKG-INFO
    writing dependency_links to pip-egg-info/MyUtils.egg-info/dependency_links.txt
    writing top-level names to pip-egg-info/MyUtils.egg-info/top_level.txt
    writing manifest file 'pip-egg-info/MyUtils.egg-info/SOURCES.txt'
    error: package directory 'my_utils' does not exist
    ----------------------------------------
ERROR: Command "python setup.py egg_info" failed with error code 1 in /private/var/folders/mz/hvngrdl93zvcjxv3bxk2z7t80000gn/T/pip-req-build-oiwltx6j/
```

  + https://docs.python.org/3/distutils/examples.html
  + https://docs.python.org/3/installing/index.html#installing-index
