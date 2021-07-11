# FROM alpine:latest
# FROM paritytech/ci-linux:production

FROM ubuntu:18.04
LABEL maintainer="warun@ubinix.com"

COPY ./target/release/node-template /node-template

CMD [ "/node-template", "--dev", "--ws-external"]

# docker tag chainlink-polkadot ubinix5warun/chainlink-polkadot
# docker push ubinix5warun/chainlink-polkadot