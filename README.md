# Cirrus Trainer — Render + GitHub

## Publicação pelo celular ou computador

1. Crie um repositório no GitHub (de preferência **privado**).
2. Envie **os arquivos que estão dentro desta pasta para a raiz do repositório**; não envie apenas o ZIP.
3. No Render, escolha **New > Blueprint**, conecte o repositório e confirme a implantação indicada em `render.yaml`.
4. Alternativamente, escolha **New > Static Site**, conecte o repositório, use **Build Command:** `echo ready` e **Publish Directory:** `.` (ponto).
5. Aguarde o deploy e abra a URL HTTPS `*.onrender.com` fornecida pelo Render.
6. No Chrome Android, menu > Adicionar à tela inicial / Instalar app. No Safari iOS, Compartilhar > Adicionar à Tela de Início.

## Conteúdo e limitações

Este é um **protótipo**, não a versão completa solicitada: inclui 5 questões de demonstração, 1 ordenação parcial do SR22 e a listagem dos 4 documentos, **sem os PDFs incorporados**. O idioma PT/EN pode ser alternado. A seção de biblioteca ainda não oferece download. SR20 e SR22 estão presentes; Montaer ainda não foi implementado. Não existe backend, login ou banco de dados.

**Importante:** não publique PDFs de fabricantes em repositório público sem autorização. O guia Garmin, por exemplo, restringe distribuição comercial não autorizada. O conteúdo técnico é para estudo, nunca para consulta operacional durante voo. Verifique sempre aplicabilidade, matrícula, série e revisão do POH/AFM.

## APK

O Render hospeda a PWA, mas não gera APK. Um APK requer um projeto Android e compilação por Android SDK/Gradle ou serviço CI configurado.
