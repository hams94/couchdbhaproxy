FROM haproxy:latest

# Copie du fichier self.pem (fichier du certificat ssl, pour l'instant c'est un faux) vers /usr/local/etc/haproxy/self.pem 
COPY self.pem  /usr/local/etc/haproxy/self.pem   

COPY haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg

