Module `auth.db2`
=================

These file load credentials for database db2 and make connection db2

Expand source code

    '''
    These file load credentials for database  db2 and make connection db2
    '''
    import firebase_admin
    from firebase_admin import credentials
    from firebase_admin import firestore
    cred = credentials.Certificate('./auth/serviceAccountKey.json')
    app = firebase_admin.initialize_app(cred)
    db = firestore.client()

Index
=====

*   ### Super-module
    
    *   `[auth](index.html "auth")`



Module `auth.LogAuth`
=====================

These file load credentials of authenication system The sensitive information keys are removed

Expand source code

    '''
    These file load credentials of authenication system
    The sensitive information keys are removed
    '''
    import pyrebase
    config ={
        "apiKey": "AIzaSyDfdwSin_37pjwdjNOMtVdmVpbma8KExL4",
        "authDomain": "authenication-demo-52769.firebaseapp.com",
        "projectId": "authenication-demo-52769",
        "storageBucket": "authenication-demo-52769.appspot.com",
        "messagingSenderId": "198740956473",
        "appId": "1:198740956473:web:5da359eff85076351684e8",
        "measurementId": "G-G6PZ3Q2B53",
        "databaseURL":""
    }
    
    firebase = pyrebase.initialize_app(config)
    auth = firebase.auth()

Index
=====

*   ### Super-module
    
    *   `[auth](index.html "auth")`



