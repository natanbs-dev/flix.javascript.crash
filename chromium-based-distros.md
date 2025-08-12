### **1. Ative as Flags de Aceleração por GPU e Codecs Avançados**
Acesse as flags experimentais digitando na barra de endereços:  
```
chrome://flags
```  
Pesquise e ative as seguintes flags:  
- **`Override software rendering list`** → **Enabled**  
  - Força a aceleração por GPU mesmo em sistemas não oficialmente suportados .  
- **`Hardware-accelerated video decode`** → **Enabled**  
  - Usa a GPU para decodificar vídeos (reduz consumo de CPU e melhora performance em 4K).  
- **`Enable Zero-copy rasterizer`** → **Enabled**  
  - Permite que o Chrome escreva diretamente na GPU, melhorando desempenho (pode causar instabilidade) .  
- **`GPU Rasterization`** → **Enabled**  
  - Descarga a renderização para a GPU (ideal se você tem uma placa dedicada) .  

**Reinicie o navegador** após aplicar as alterações.  

---
