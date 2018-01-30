# Adhell 2 Oreo Hacky Fix

[Commit Page](https://github.com/MilanParikh/Adhell2/commit/223c1d7e382759ac12ca62b7651440df30e9eea8)

## Description
Knox Standard SDK version is not publicly released until Oreo is officially released. Hence, I thought of just directly bypassing the version checking, which (I think) originally was intended to deter unsupported old devices/Touchwiz users. I deduced that since Oreo Beta and Note 8 comprised of a very niche userbase, the "fix" wouldn't be spread to the unintended users. From the source code, I followed the crumbs source for the version checker, and just turned all the false to true for unsupported versions. I also learned that Samsung apparently, on their server, keeps track of known Adhell 2 package names to block license verifications, which I then learned to rename the entire app package, which took a while as Android Studio is kind of buggy with the Refactor tool. (Bypass does not fix timed crashes, which was fixed later by another person).

### Original Write-Up 
[Image](https://i.imgur.com/7oyq3s9.jpg)
