# Calculadora de Preços

Uma aplicação web responsiva para comparar preços de produtos por peso, volume, porção e unidade, além de calcular descontos e rendimentos.

## 🚀 Funcionalidades

### 📊 Comparação por Peso/Volume
- Compare dois produtos pelo preço por quilograma
- Ideal para produtos vendidos por peso (arroz, feijão, açúcar, etc.)

### 🍽️ Comparação por Porção
- Compare produtos pelo preço por porção
- Perfeito para iogurtes, refeições prontas, etc.

### 📦 Comparação por Unidade
- Compare produtos pelo preço por unidade individual
- Útil para pacotes com múltiplas unidades (biscoitos, barras de cereal, etc.)

### 💰 Calculadora de Desconto
- Calcule o percentual de desconto real
- Veja quanto você está economizando em reais

### 🥄 Calculadora de Rendimento
- Calcule quantas porções um produto oferece
- Descubra o preço por porção baseado no peso total

## 🎨 Design

- **Interface responsiva** otimizada para dispositivos móveis
- **Design moderno** com Tailwind CSS
- **Navegação por abas** para fácil acesso às diferentes calculadoras
- **Resultados visuais** com destaque para a melhor opção

## 🛠️ Tecnologias Utilizadas

- **React 19** - Framework JavaScript
- **Tailwind CSS** - Framework de CSS utilitário
- **Lucide React** - Ícones modernos
- **Vite** - Build tool rápido

## 📱 Como Usar

1. **Selecione o tipo de comparação** clicando em uma das abas (Peso, Porção, Unidade, Desconto, Rendimento)
2. **Preencha os dados** dos produtos que deseja comparar
3. **Clique em "Calcular"** para ver os resultados
4. **Analise o resultado** que mostra qual produto oferece melhor custo-benefício

## 🚀 Deploy na Vercel

### Pré-requisitos
- Conta no GitHub
- Conta na Vercel

### Passos para Deploy

1. **Suba o código para o GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/seu-usuario/calculadora-precos.git
   git push -u origin main
   ```

2. **Conecte com a Vercel:**
   - Acesse [vercel.com](https://vercel.com)
   - Faça login com sua conta GitHub
   - Clique em "New Project"
   - Selecione o repositório da calculadora
   - Configure as seguintes opções:
     - **Framework Preset:** Vite
     - **Build Command:** `npm run build`
     - **Output Directory:** `dist`
   - Clique em "Deploy"

3. **Configurações adicionais (se necessário):**
   - A Vercel detecta automaticamente projetos Vite
   - Não são necessárias configurações especiais

### Deploy Automático
Após a configuração inicial, qualquer push para a branch `main` irá automaticamente fazer o deploy da nova versão.

## 🔧 Desenvolvimento Local

### Instalação
```bash
# Clone o repositório
git clone https://github.com/seu-usuario/calculadora-precos.git

# Entre no diretório
cd calculadora-precos

# Instale as dependências
npm install
```

### Executar em desenvolvimento
```bash
npm run dev
```

### Build para produção
```bash
npm run build
```

### Preview do build
```bash
npm run preview
```

## 📝 Estrutura do Projeto

```
calculadora-precos/
├── public/
├── src/
│   ├── components/
│   ├── assets/
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── tailwind.config.js
└── vite.config.js
```

## 🤝 Contribuição

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🎯 Próximas Funcionalidades

- [ ] Histórico de comparações
- [ ] Exportar resultados em PDF
- [ ] Comparação de mais de 2 produtos
- [ ] Calculadora de inflação de preços
- [ ] Modo escuro
- [ ] Suporte a diferentes moedas

---

Desenvolvido com ❤️ para ajudar você a economizar nas compras!
