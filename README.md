![Image of cuckoo-droid](https://github.com/idanr1986/cuckoo-droid/blob/master/documentation/book/src/_images/logo/cuckoo.png?raw=true)


CuckooDroid - Automated Android Malware Analysis.
=================================================
Contributed By Check Point Software Technologies LTD.

CuckooDroid is an extension of Cuckoo Sandbox the Open Source software for automating analysis of suspicious files, CuckooDroid brigs to cuckoo the capabilities of execution and analysis of android application.

Installation - Easy integration script:

    git clone --depth=1 https://github.com/cuckoobox/cuckoo.git cuckoo
    cd cuckoo
    git remote add droid https://github.com/idanr1986/cuckoo-droid
    git pull --no-edit -s recursive -X theirs droid master 
    cat conf-extra/processing.conf >> conf/processing.conf
    cat conf-extra/reporting.conf >> conf/reporting.conf
    rm -r conf-extra
    echo "protobuf" >> requirements.txt

Documentation
=============
- CuckooDroid - http://cuckoo-droid.readthedocs.org/
- Cuckoo Sandbox - http://cuckoo.readthedocs.org/

You are advised to read the Cuckoo Sandbox documentation before using CuckooDroid!

Powered by:
===========
- Androguard -> https://code.google.com/p/androguard/
- Google Play Unofficial Python API -> https://github.com/egirault/googleplay-api

Credit 
======
- botherder for linux_analyzer_dev -> https://github.com/cuckoobox/cuckoo/tree/linux_analyzer_dev

Authors
=======
- Idan Revivo - idanr@checkpoint.com (twitter: idanr86)
- Ofer Caspi oferc@checkpoint.com (twitter: @shablolForce)
