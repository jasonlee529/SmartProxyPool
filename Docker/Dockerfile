FROM python:3.7
WORKDIR /usr/src/app
COPY . .

ENV DEBIAN_FRONTEND noninteractive
ENV TZ Asia/Shanghai

RUN pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple

EXPOSE 35050
EXPOSE 36050

CMD [ "python", "Src/Run/main.py" ]
