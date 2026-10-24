# LOTTAN para Android

Site público: https://lottan-lit.github.io/lottan-app/

## 0.2.1 — ajuste de layout e navegação Android

- Áreas de sistema aplicadas ao contêiner nativo, evitando sobreposição da interface WebView.
- Navegação do Android em modo imersivo com revelação transitória por gesto, tanto na biblioteca como no leitor.
- Aparência das barras e modo imersivo gerenciados juntos, sem a troca de tema cancelar a ocultação.
- Layout com altura medida dentro da área útil; barra da LOTTAN em espaço próprio, sem sobrepor o conteúdo.
- Tela inicial mais compacta, hierarquia de texto, capas e espaçamentos revisados.
- Mesmo pacote e mesma assinatura da 0.2.0: instalar por cima, sem desinstalar.

Compilação e assinatura verificadas. Testes de interface em larguras de 360 e 393 px; integração JavaScript conferida. A ocultação nativa e o layout ainda precisam de validação no Moto G84 físico.

Requer Android 8+ com Android System WebView atualizado. APK de teste fora da Play Store.
