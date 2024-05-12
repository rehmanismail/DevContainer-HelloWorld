# # FROM ubuntu:22.04
# # RUN mkdir rehmanismail
# # RUN atp update


FROM python:3.12
RUN pip install poetry 
WORKDIR /code
COPY . /code/
# ADD ./helloworld /code/helloworld/
RUN poetry install
CMD [ "poetry","run","uvicorn","helloworld.main:app","--host","0.0.0.0" ]

# Container s bahir
# CTRL P + Q

# Contain k ander janay ki
# docker exec -it af4e---- /bin/bash/  sh

# Running Container s image build
# docker commit a4f2 imagefromcontainer

# FROM python:3.12

# LABEL maintainer="lahore-class"

# WORKDIR /code

# COPY . /code/

# RUN pip install poetry

# # RUN poetry config virtualenvs.create false
# RUN poetry config virtualenvs.create false

# # RUN poetry install
# RUN poetry install --no-interaction --no-root


# CMD ["poetry", "run", "uvicorn", "src.main:app", "--host", "0.0.0.0", "--reload"]