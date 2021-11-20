FROM python
RUN pip install flask
COPY  ./templates /home/myapp/templates/
COPY  design_app.py /home/myapp/
EXPOSE 5050
CMD python3 /home/myapp/design_app.py
