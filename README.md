# 🛒 Cupons WPP — Gerador de Mensagens para WhatsApp

Ferramenta web para gerar mensagens formatadas de cupons e promoções prontas para enviar no WhatsApp. Funciona 100% no navegador, sem backend, sem instalação.

---

## ✨ O que é

- Preencha os dados da oferta (produto, preço, cupom, link de afiliado, imagem)
- Visualize em tempo real o preview no estilo bolha do WhatsApp
- Copie a mensagem com um clique e cole direto no WhatsApp
- Histórico local das últimas 5 mensagens geradas (salvo no navegador)
- Campos opcionais com toggle — desative o que não precisar
- Botão separado para copiar a imagem do produto

---

## 🚀 Como usar

1. Acesse o app pelo link público (GitHub Pages)
2. Selecione a plataforma (Mercado Livre, Shopee, Amazon…)
3. Preencha os campos desejados — use os toggles para desativar campos opcionais
4. Clique em **Gerar Mensagem**
5. Clique em **Copiar Mensagem** e cole no WhatsApp
6. Se houver imagem, clique em **Copiar Imagem** separadamente

---

## 🔄 Como atualizar e publicar novas versões

Após editar qualquer arquivo (`index.html`, etc.):

```bash
# 1. Entre na pasta do projeto
cd "Envio Cupons"

# 2. Adicione as mudanças
git add .

# 3. Crie um commit descrevendo o que mudou
git commit -m "descrição da mudança"

# 4. Envie para o GitHub
git push origin main
```

O GitHub Pages atualiza automaticamente em até **1–2 minutos** após o push.

---

## 🛠️ Tecnologias utilizadas

| Lib | Uso |
|---|---|
| Tailwind CSS | Estilização |
| Alpine.js | Reatividade |
| Font Awesome 6 | Ícones |
| SweetAlert2 | Modais de confirmação |
| Toastify.js | Notificações |
| Tippy.js | Tooltips |

Todas carregadas via CDN — nenhuma instalação necessária.

---

## 📄 Licença

Uso pessoal. Feito para facilitar o envio de cupons de afiliados no WhatsApp.
