# MY-Machine-learning-
Requeried softwares
1.  [git hub]
2.  [heroku account]
3.  [VS code IDE]
4.  [git cli]


'''''
creating conda enivronment
'''''

'''''
conda create -p venv python==3.11 -y
''''

'-p' creates new vertual enivronment
'''''

conda activate venv/
'''''

'''''
to check conda env 'conda info --env'
'''''
to install requirement files
'''''
''''
pip install -r requirements.txt


'''''
to add files to git 
''''
git add <file name>


'''''
To check status

'''''
get status
'''''
To ccreate new version 
''''
git commit -m 'message'
'''''
To send changes to github
'''''
git push origin main
'''''
To check remote url
''''

git remote -v
'''''


TO setup CI/CD pipeline in heroku we need 3 info
1. Heroku_Email=naveenkokku1998@gmail.com
2. Heroku_API_KEY= HRKU-4d7fc25e-e7bb-4650-b11d-cee55c7e9be4
3. Heroku_APP_NAME_=ml-project

'''''''

BUILD DOCKER IMAGE
'''

docker build -t <image_name>:<tagname>
'''
>Note : image name must be lower case 
''''
To list docker image
'''
docker images
'''

Run docker image
'''
docker run -p 5000:5000 -e PORT=5000 
''''
