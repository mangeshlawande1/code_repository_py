PS C:\Users\mangesh.l\Desktop\Read_P\01_vitrual> python --version
1. make virtual env: 
    >>  python -m venv .venv
2. TO activate :
    >> .venv\Scripts\activate
    2.1 install dependency, create services
    >> pip install flask requests

    2.2 another way :
     >> pip install -r requirements.txt
3. To deactivate
    >> deactivate

## Always works in venv

**Traditional way** --> using venv

**Another way** --> using uv

**Q. How to organize structures and folders in python**-->
    - organize ur python code 
    - shop
        run.py  -- start app
        server.py 
        processing/
        utils/
         __init__.py
           - It will differentiate processing with the utils 
           - File with classes having some functions  
            1. **modules** : (run.py, server.py, etc, every single file called modules) A normal python file.  
            2. **packages** : any folder having __init__.py known as package, mostly in utils. 

**Namespaces & scopes**:
    something which cannot be accessible to any-one

## 13. PEP8 & Zen of Python 
**4 spaces instead of tabs**
**Use meaningful name for methods**
**formatters**

Zen of python
>>python
>> import this

## Always write simple code 

