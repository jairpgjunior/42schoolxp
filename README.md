# 42 School. My personal Guide

## 42 Norm Compliance Checker

Avalie o código fornecido de acordo com as regras da *Norm* da 42. Verifique se o código segue os padrões abaixo e aponte quaisquer violações.

### ✅ O que fazer:
- **Nomeação:** Use `snake_case`. Prefixe nomes corretamente (`s_` para `struct`, `t_` para `typedef`, `e_` para `enum`, `u_` para `union`, `g_` para globais).
- **Formatação:** 
  - Máximo de **80 caracteres por linha**.
  - Indentação com **TAB (ASCII 9)**.
  - **Chaves `{}`** sempre em novas linhas, exceto em `struct`, `enum`, `union`.
- **Funções:** 
  - Máximo de **25 linhas**.
  - Máximo de **4 parâmetros**.
  - Máximo de **5 variáveis declaradas**.
  - Retorno dentro de `()` (ex.: `return (x);`).
- **Arquivos:** 
  - **Máximo 5 funções por .c**.
  - Nenhum `.c` deve incluir outro `.c`.
- **Makefile:** Deve ter regras `all`, `clean`, `fclean`, `re`.

### ❌ O que NÃO fazer:
- **Proibido:**  
  - `for`, `do...while`, `switch/case`, `goto`, operador ternário `? :`.
  - VLAs (*Variable Length Arrays*).
  - Declarações implícitas (`int x = argc > 5 ? 0 : 1;` 🚫).
- **Má práticas:**  
  - **Declarações de variáveis no meio da função** (devem estar no início).
  - **Múltiplas instruções por linha** (cada instrução em uma linha).
  - **Espaços extras** no final das linhas ou dentro de linhas vazias.

---

### 📌 **Instruções para avaliação**
1. **Liste as violações da Norm encontradas** e explique o erro.
2. **Sugira correções** para que o código esteja conforme a Norm.
3. **Se o código estiver correto**, apenas confirme a conformidade.

Saída esperada: uma análise objetiva com feedback claro sobre o código fornecido.
