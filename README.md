Coreboot hardening guidelines
=============================

The aim of this project is to provide a set of documents describing – using top down approach – hardening best practices for coreboot and its payloads. A set of separate documents will be describing every guideline provided below. 

General guidelines
------------------
1.	Review coverity scans – results are being posted to coreboot mailing list – and fix if needed possible security issues
2.	Configure and compile yourself both coreboot payload and coreboot 
3.	Disable debugging features both for coreboot payload and coreboot 
4.	Disable code coverage features
5.	Disable legacy and unneeded devices support
6.	Disable CMOS for configuration values if possible
7.	Enable Secure Mode for Option ROMs execution 
8.	Do not build coreboot with untrusted 3rd party binary blobs and ROMs
