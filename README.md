# microservices-mensageria-escalabilidade-mvpconf-2026
Conteúdos da apresentação "Microservices, Mensageria e Escalabilidade com Azure + Kubernetes + KEDA".

Tecnologias e tópicos abordados: Kubernetes, Microservices, KEDA, Escalabilidade, Microsoft Azure, Grafana, Prometheus, Azure Queue Storate, RabbitMQ, Apache Kafka, Azure Service Bus, Azure Event Hubs...

Links importantes:
- Aplicação utilizada nos testes de escalabilidade: **https://github.com/renatogroffe/dotnet10-worker-azurequeuestorage_generic-consumer**
- Testes de carga com envio de mensagens em massa para uma fila do Azure Queue Storage: **https://github.com/renatogroffe/k6-loadtests-azuredevops-azurequeuestorage-html-dashboard**
- Instruções para configuração do KEDA e de sua integração com Grafana + Azure Managed Prometheus: **https://github.com/renatogroffe/keda_operator-aks-managed_prometheus**
- Manifestos para deployment da aplicação e configuração do Scaled Object: **https://github.com/renatogroffe/kubernetes-keda-azurequeueatorage_consumergenerico**
