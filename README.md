# Zero_Day First Test with 
*  First Test to  repo i.e.  Zero_Day *

1. Accessible via [SSH] (git@github.com:seekersalama/zero_day.git) 
2. Accessible via [HTTPS] (https://github.com/seekersalama/zero_day.git)
# AND ALSO
1. A local copy is also mainntained for ease of development
# Verify new remote
git remote -v

## Initial pull/pull
~~~~
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/seekersalama/zero_day.git
git push -u origin main
~~~~
## Subsequent Update
~~~~
git remote add origin https://github.com/seekersalama/zero_day.git
git branch -M main
git push -u origin main
~~~~