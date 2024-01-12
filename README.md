# mainmodule

git reset 1
git reset 2
git revert 1


```html
 1390  take sunmodulesdemo

 1399  brew install gh
 1401  gh repo delete submoduleB
 1404  gh repo list
 1410  cat .gitmodules
 1411  git submodule --help
 1413  ga .; gc -m 'push with submodule';gp
 1414  ga .; gc -m 'push ';gp
 1417  clear
 1418  gh repo delete submoduleA
 1419  gh repo delete mainmodule
 1421  del mainmodule
 1422  del submoduleA
 1423  take mainmodule
 1424  git init
 1425  gh repo create mainmodule  --public --description "demo submodules"
 1426  echo "# mainmodule" >> README.md\ngit init\ngit add README.md\ngit commit -m "first commit"\ngit branch -M main\ngit remote add origin https://github.com/nat2k5us/mainmodule.git\ngit push -u origin main
 1427  take submoduleA
 1429  gh repo create submoduleA  --public --description "demo submodules"
 1430  echo "# submoduleA" >> README.md\ngit init\ngit add README.md\ngit commit -m "first commit"\ngit branch -M main\ngit remote add origin https://github.com/nat2k5us/submoduleA.git\ngit push -u origin main
 1431  code mainmodule
 1432  code submoduleA
 1433  git submodule add https://github.com/nat2k5us/submoduleA.git
 1435  ga .; gc -m 'first commit ';gp
 1438  ga .; gc -m 'second commit ';gp
 1440  ga .; gc -m 'with submodules ';gp
 1443  git checkout main
 1444  git pull
 1446  ga .; gc -m '3 rd  commit ';gp
 1448  submoduleA
 1449  git submodule update
 1451  ga .; gc -m 'submodule updated ';gp
 1452  git submodule status
```
