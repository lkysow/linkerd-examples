FROM library/golang:1.6.0
RUN ["mkdir", "-p", "/src"]
COPY reqz/main.go /src/
RUN ["go", "build", "-o", "/usr/bin/reqz", "/src/reqz.go"]
ENTRYPOINT ["/usr/bin/reqz"]
