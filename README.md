# What is it?

This is a PEAR module for Blowfish encryption/decryption, minus the PEAR.  I claim nothing on this code.  All I did was pull out some PEAR specific error calls and replace them with Exceptions.

All glory to Matthew Fonda and Philippe Jausions.  And the hypno toad.

To get the PEAR package version, go to http://pear.php.net/package/Crypt_Blowfish/

# Testing

I ran the tests, and you can too!

    jmhobbs@asuka:~/Desktop/No-PEAR-Crypt_Blowfish/tests$ pear run-tests blowfish.phpt
    Running 1 tests
    PASS Test Crypt_Blowfish[blowfish.phpt]
    TOTAL TIME: 00:01
    1 PASSED TESTS
    0 SKIPPED TESTS
