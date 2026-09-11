# Comprovante — estrutura inicial
Rotas: /cadastro, /login, /painel, /adm e /localizacao?ref=SLUG.
1. Edite config.js com URL e chave pública do Supabase.
2. Execute supabase/schema.sql.
3. Crie a primeira conta em /cadastro e promova-a a admin pelo SQL indicado.
4. Publique na Vercel.
A página pública solicita geolocalização somente após clique e de forma explícita. Nunca coloque service_role/sb_secret no frontend.
