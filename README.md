# dev-traefik-http
Repositório para Traefik padrão. 
Contem:
- HTTP
- Dashboard na porta 8080
- Habilitado Log
- Redes distintas para diferentes serviços

Por motivos de segurança, o ideal é que cada serviço que você suba esteja em uma rede separada. Mas não esqueça que a rede tem que estar presente tanto na Stack do serviço quanto na Stack do Traefik
