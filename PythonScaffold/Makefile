install:
	pip install --upgrade pip &&\
		pip install -r requirements.txt
install-azure:
	pip install --upgrade pip &&\
		pip install -r requirements.txt
format:
	black *.py
lint:
	pylint  --disable=R,C Helloworld.py
test: 
	python -m pytest -vv -cov=hello Helloworld-tst.py
