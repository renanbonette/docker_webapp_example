docker build -t dockerwebapp:v1.0 .
docker images
docker run -d -p 5000:5000 id-da-imagem-criada

Executar o comando:
curl -0 http://localhost:5000
