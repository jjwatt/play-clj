FROM clojure:lein
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY project.clj .
RUN lein deps
COPY . .
CMD ["lein","repl"]
