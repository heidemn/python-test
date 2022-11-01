.PHONY: run
run:
	uvicorn main:app --reload

prod:
	gunicorn -w 4 -k uvicorn.workers.UvicornWorker main:app

deps:
	pip3 install -r requirements.txt
