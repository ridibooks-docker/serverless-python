FROM python:3.6

RUN pip install pipenv
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash -
RUN apt install -y nodejs

RUN npm config set unsafe-perm true
RUN npm install -g serverless

