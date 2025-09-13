# 🧾 Extração de Entidades Nomeadas – Azure AI Language

## 🔧 Ferramenta Utilizada
Azure AI Foundry – Language Playground  
Modo: Extract Named Entities

## 📝 Texto Analisado
The Royal Hotel, London, United Kingdom 5 / 6 / 2018 This is an old hotel (has been around since 1950's) and the room furnishings are average...

## 📊 Entidades Extraídas
| Entidade             | Tipo         | Confiança |
|----------------------|--------------|-----------|
| The Royal Hotel      | Organization | Alta      |
| London               | Location     | Alta      |
| United Kingdom       | Location     | Alta      |
| British Museum       | Location     | Média     |
| 5 / 6 / 2018         | Date         | Alta      |

## 💡 Observações
- O serviço identificou corretamente locais e datas.
- Útil para categorizar avaliações por localização e período.

## 🧠 Insight
A extração de entidades permite organizar grandes volumes de texto por categorias relevantes, como locais, datas e organizações.
