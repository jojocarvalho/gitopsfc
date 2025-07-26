
- Para cirar a imagem docker:
  - docker build -t jojo/gitops:latest .
- Para rodar a imagem
  - docker run --rm -p 8080:8080 jojo/gitops:latest


- Comando para rodar o ArgoCD:
  - kubectl port-forward svc/argocd-server -n argocd 8080:443
  - user: admin
  - senha: 2XSEEedg16TCMNmT
