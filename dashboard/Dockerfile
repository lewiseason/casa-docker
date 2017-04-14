FROM ruby:alpine
WORKDIR /usr/src/dashboard
RUN apk --update add tzdata nodejs git g++ musl-dev make
RUN git clone https://github.com/lewiseason/casa-dashboard.git /usr/src/dashboard
RUN bundle install
CMD rackup
