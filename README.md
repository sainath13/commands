## REACT-NATIVE <br/> 
react-native init projectName <br/>
react-native run-android <br/>
adb shell input keyevent 82 <br/>



## ngrok <br/>
./ngrok http 3000 <br/>

## pgsql<br/>
initdb db (in _projects) <br/>
pg_ctl -D db/ -l logfile start <br/>
pg_ctl postgres<br/>

createdb saitama <br/>

psql => now the console will start

CREATE USER postgres;
ALTER USER postgres WITH SUPERUSER;
ALTER USER postgres PASSWORD 'postgres';
\q


## redis<br/>
redis-serve<br/>

## git merging branch test<br/>
git checkout master<br/>
git pull origin master<br/>
git merge test<br/>
git push origin master<br/>

## git reseting current code to some previous commit: last working thing<br/>
git log -line
git reset --hard commitId
