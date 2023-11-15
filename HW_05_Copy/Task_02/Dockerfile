FROM ubuntu:latest
	LABEL manteiner="polina.timofeeva11@gmail.com"
	RUN apt-get update 
	RUN apt-get -y install g++ nano net-tools inetutils-ping
	WORKDIR /root/test
	COPY main.cpp .
	RUN g++ main.cpp -o main
	CMD ["./main"]