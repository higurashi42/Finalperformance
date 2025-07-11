# Finalperformance
vue create surf-wave-app 
cd surf-wave-app

# git初期化（まだなら）
git init
git remote add origin https://github.com/higurashi42/Finalperformance.git
git add .
git commit -m "アプリ本体を追加"
git push -u origin main
firebase login
firebase init hosting
npm run build  # または yarn build
firebase deploy