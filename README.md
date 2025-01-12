# smartnote

افتح ملف فاضي 
git clone  https://github.com/CodeWithClinton/react-note-app
git clone https://github.com/CodeWithClinton/notes-crud-api
ls react../
npm i
node -v
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
 nvm install --lts
 nvm use --lts
npm install vite
npm run dev
خلي terminal  هاد مفتوح و افتح واحد تاني 
cd note.../
python3 --version (output Python 3.8.10)
source venv/bin/activate
telecharge file 
pip install -r requirements.txt
pip install django-cors-headers
pip install djangorestframework
pip install markdown   
pip install django-filter
pip install Django
cd yt_..
افتح setting.py
ابحت عن  فقرة متل كدة  و الص فيها هي يلي بعت انا : 
CORS_ALLOWED_ORIGINS = [
"http://localhost:5173",
"http://127.0.0.1:5173",
]
cd react_../
افتح src/app.jsx
ابحت عن هاد :
  const deleteNote = (slug) => {
    axios
      .delete(`http://127.0.0.1:8008/notes/${slug}`)
      .catch((err) => console.log(err.message));
  };
و ضيف / ; و تصير كدة : 
  const deleteNote = (slug) => {
    axios
      .delete(`http://127.0.0.1:8008/notes/${slug}/`)
      .catch((err) => console.log(err.message));
  };
cd notes_.../
python manage.py runserver 8008
