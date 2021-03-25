FROM ubuntu:18.04

RUN apt-get update && apt-get install -y curl
RUN echo 'echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website;' > script.sh

CMD ["/bin/bash", "./script.sh"]