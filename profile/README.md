## Github organizacional do Instituto Pereira Passsos
para solicitar acesso ou resolver problemas: leonardo.aucar@prefeitura.rio ou pesquisaeavaliacao.ipp@prefeitura.rio

## Regras
OBS: caso deseje adicionar outra nomenclatura, favor informar no(s) e-mail(s) acima

### Nomenclatura de repositorios
#### Para fluxos de dados - camadas bronze e silver:
<li>pipeline_exemplo</li>
<li>etl_exemplo</li>

#### Para produtos:
<li>analise_exemplo --> relatórios descritivos ou de avaliação de impacto (nesse caso usar análise_impacto_ ) </li>
<li>dashboard_exemplo --> dashboards e painéis</li>
<li>webpage_exemplo --> para hubs, experiences, sites etc</li>

#### Para utilidades gerais
<li>client_exemplo --> para clientes de APIs</li>
<li>crawler_exemplo --> para raspadores de dados e outros crawlers</li>
<li>utils_exemplo --> para utilidades de projetos</li>

### Arquivos que devem estar no seu gitignore
<li>Bases de dados</li>
<li>arquivos .env</li>
<li>Não hospedar arquivos grandes (+50mb)</li>
<li>Não hospedar tabelas de dados ou qualquer tipo de tabela resultado</li>

### Segurança
<li>Todos devem implementar segurança de dois fatores</li>
<li>NUNCA compartilhar senhas ou contas - 1 pessoa, 1 usuário</li>
<li>NUNCA compartilhar ou dar commit em arquivos .env</li>

### Recomendação de commits
<li>TIPO COMMIT: descrição da atualização</li>

<b>Tipo	Quando usar</b>
<li>FEAT -	Uma nova funcionalidade para o usuário</li>
<li>FIX	- Correção de um bug</li>
<li>DOCS -	Mudanças apenas na documentação (README, comentários, etc.)</li>
<li>STYLE	- Formatação, espaços, ponto e vírgula — sem mudar lógica</li>
<li>REFACTOR - Reestruturação de código sem alterar comportamento</li>
<li>PERF -	Melhoria de performance</li>
<li>TEST -	Adição ou correção de testes</li>
<li>BUILD -	Mudanças no sistema de build ou dependências (npm, webpack, etc.)</li>
<li>CI -	Mudanças em arquivos/scripts de integração contínua</li>
<li>CHORE -	Tarefas gerais de manutenção, sem afetar código de produção</li>
<li>REVERT	Reverte um commit anterior</li>

### Outras boas práticas
<li>Evite arquivos de formatos proprietários como XLSX, prefira csv</li>
<li>Inclua sempre um readme.md sobre seu projeto</li>
<li>Inclua sempre um requirements.txt</li>
<li>Siga boas práticas de organização e documentação do seu código</li>
