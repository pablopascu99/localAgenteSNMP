FROM python

WORKDIR /receptor

COPY ./receptor/requirements.txt .
RUN pip install -r requirements.txt

COPY . .

EXPOSE 1620

CMD [ "python", "-u", "./receptor/snmpGet.py"]