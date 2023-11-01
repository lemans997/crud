# CRUD

## 프로젝트 구조 작성

1. 프로젝트 폴더 생성
2. 프로젝트 폴더를 vscode로 열기
    - `.gitignore`, `README.md` 만들기

3. django 프로젝트 생성
```
django-admin startproject <pit-name> . 
```

4. 가상환경 설정
```
python -m venv venv
```

5. 가상환결 확성화
```
source venv/Script/activate
```

6. 가상환경에 django 설치
```
pip install django
```

7. 서버 실행 확인
```
python manage.py runserver
```

8. 앱 생성
```
django-admin startapp <app-name>
```

9. 앱등록 => `settings.py`
```python
INSTALLED_APPS = [
    ....
    '<app-name>'
```