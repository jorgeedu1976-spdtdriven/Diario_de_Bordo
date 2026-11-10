<!DOCTYPE html>
<html lang="pt-BR"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Diário de Bordo: Manual de uso</title>
<style>
:root{--bg:#F5F7FA;--cd:#fff;--tx:#1B2430;--mu:#5B6776;--ac:#2557A7;--bd:#DDE3EA;--sf:#E9EEF6;--wn:#B3361F}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#12161C;--cd:#1B222B;--tx:#E8EDF3;--mu:#9AA7B6;--ac:#7FAEF0;--bd:#2D3846;--sf:#222B37;--wn:#FF8F7A}}
:root[data-theme="dark"]{--bg:#12161C;--cd:#1B222B;--tx:#E8EDF3;--mu:#9AA7B6;--ac:#7FAEF0;--bd:#2D3846;--sf:#222B37;--wn:#FF8F7A}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;background:var(--bg);color:var(--tx);font:17px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,Arial,sans-serif}
.w{max-width:780px;margin:0 auto;padding:40px 20px 80px}
h1{font-size:34px;line-height:1.15;margin:0 0 8px}
h2{font-size:24px;margin:48px 0 12px;padding-top:8px;border-top:1px solid var(--bd)}
h3{font-size:18px;margin:0 0 4px}
p{margin:8px 0}.lead{font-size:19px;color:var(--mu)}
a{color:var(--ac)}
nav{background:var(--cd);border:1px solid var(--bd);border-radius:12px;padding:14px 18px;margin:24px 0}
nav b{display:block;margin-bottom:6px}nav ol{margin:0;padding-left:20px;columns:2}
.g{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px;margin:14px 0}
.c{background:var(--cd);border:1px solid var(--bd);border-radius:12px;padding:16px}
.c p{color:var(--mu);margin:0;font-size:16px}
.n{display:inline-block;font-weight:700;color:var(--ac);margin-bottom:4px}
.fl{display:flex;align-items:stretch;gap:10px;flex-wrap:wrap;margin:14px 0}
.fl .c{flex:1;min-width:170px}.fl .ar{align-self:center;font-size:28px;color:var(--ac)}
.tip{background:var(--sf);border-radius:10px;padding:12px 16px;margin:14px 0}
.tip.wn b{color:var(--wn)}
code,kbd{font:15px ui-monospace,Menlo,Consolas,monospace;background:var(--sf);padding:2px 7px;border-radius:6px}
ol.st{padding-left:22px}ol.st li{margin:6px 0}
details{background:var(--cd);border:1px solid var(--bd);border-radius:10px;padding:12px 16px;margin:8px 0}
summary{cursor:pointer;font-weight:600}
footer{margin-top:48px;color:var(--mu);font-size:14px}
@media(max-width:560px){nav ol{columns:1}h1{font-size:28px}}
</style></head><body><div class="w">

<h1>📒 Diário de Bordo</h1>
<p class="lead">Manual de uso: aulas, planejamento e provas de todas as suas turmas em um só lugar.</p>

<nav aria-label="Sumário"><b>Neste manual</b><ol>
<li><a href="#sobre">Sobre o app</a></li>
<li><a href="#comecar">Primeiros passos</a></li>
<li><a href="#telas">As telas</a></li>
<li><a href="#fluxo">Do planejamento ao diário</a></li>
<li><a href="#backup">Backup e privacidade</a></li>
<li><a href="#github">Publicar no GitHub Pages</a></li>
<li><a href="#faq">Perguntas frequentes</a></li>
</ol></nav>

<h2 id="sobre">Sobre o app</h2>
<p>O Diário de Bordo ajuda professoras e professores com várias turmas a acompanhar o ano letivo. Funciona no celular e no computador, não exige cadastro nem instalação e acompanha o modo claro ou escuro do aparelho.</p>
<div class="g">
<div class="c"><h3>🏫 Turmas</h3><p>Cada turma com nome, disciplina e cor própria.</p></div>
<div class="c"><h3>📝 Diário</h3><p>Registro das aulas dadas e da tarefa de casa.</p></div>
<div class="c"><h3>🗓️ Planejamento</h3><p>Aulas futuras com objetivos e materiais.</p></div>
<div class="c"><h3>🎯 Provas</h3><p>Provas, trabalhos e seminários com data e valor.</p></div>
</div>

<h2 id="comecar">Primeiros passos</h2>
<div class="g">
<div class="c"><span class="n">1</span><h3>Crie suas turmas</h3><p>Na aba <b>Turmas</b>, informe o nome, a disciplina e escolha uma cor.</p></div>
<div class="c"><span class="n">2</span><h3>Planeje e registre</h3><p>Agende aulas futuras em <b>Planejar</b> e registre as já dadas no <b>Diário</b>.</p></div>
<div class="c"><span class="n">3</span><h3>Agende as provas</h3><p>Cadastre provas e trabalhos com data, conteúdo e valor.</p></div>
</div>
<p>O botão flutuante no canto da tela muda conforme a aba e sempre cria um novo item daquele tipo.</p>

<h2 id="telas">As telas</h2>
<h3>Início</h3>
<p>Resumo com o número de turmas, aulas do mês, aulas planejadas e provas a aplicar. Abaixo ficam a <b>agenda</b> dos próximos compromissos (com o aviso <i>Atrasado</i> para o que já venceu), as últimas aulas e atalhos para registrar aula, planejar e criar prova.</p>
<h3>Turmas</h3>
<p>Aqui você inclui, edita e exclui turmas. Cada cartão mostra quantas aulas, planos e avaliações a turma tem.</p>
<div class="tip wn"><b>Atenção ao excluir:</b> apagar uma turma remove também todas as aulas, planos e provas dela, sem como desfazer. Faça um backup antes, se quiser guardar o histórico.</div>
<h3>Diário</h3>
<p>Lista das aulas dadas, da mais recente para a mais antiga. Cada registro tem assunto, o que foi trabalhado e tarefa de casa ou observações.</p>
<h3>Planejar</h3>
<p>Aulas futuras com tema, objetivos e materiais necessários. Os itens vencidos e ainda pendentes aparecem sinalizados.</p>
<h3>Provas</h3>
<p>Escolha o tipo (<b>Prova</b>, <b>Trabalho</b>, <b>Seminário</b> ou <b>Recuperação</b>) e informe data, conteúdo cobrado e valor ou peso. Toque em <b>✓ Aplicada</b> quando concluir; <b>Reabrir</b> desfaz.</p>
<div class="tip"><b>Dica:</b> nas abas Diário, Planejar e Provas, toque no nome de uma turma no topo para ver só os itens dela.</div>

<h2 id="fluxo">Do planejamento ao diário</h2>
<div class="fl">
<div class="c"><h3>Planejar</h3><p>Crie o plano com tema, objetivos e materiais.</p></div><span class="ar">→</span>
<div class="c"><h3>Aula dada</h3><p>Depois da aula, toque em <b>✓ Aula dada</b>.</p></div><span class="ar">→</span>
<div class="c"><h3>Diário</h3><p>O plano vira registro. Acrescente o que foi trabalhado e a tarefa.</p></div>
</div>

<h2 id="backup">Backup e privacidade</h2>
<p>Os dados ficam salvos no navegador do aparelho e são privados: cada pessoa que abrir o link tem o seu próprio diário, sem acesso ao de ninguém.</p>
<ol class="st">
<li>Toque em <b>💾 Backup</b>, no topo da tela.</li>
<li>Use <b>Copiar</b> e guarde o código em um lugar seguro (um e-mail para você mesma, por exemplo).</li>
<li>Em outro aparelho, abra o app, toque em <b>Backup</b>, cole o código e use <b>Importar</b>.</li>
</ol>
<div class="tip wn"><b>Importante:</b> limpar os dados do navegador apaga o diário. Faça backups de vez em quando.</div>

<h2 id="github">Publicar no GitHub Pages</h2>
<ol class="st">
<li>Crie um repositório no GitHub (por exemplo, <code>diario-de-bordo</code>).</li>
<li>Envie o arquivo do app com o nome <code>index.html</code> (e este manual como <code>manual.html</code>, se quiser).</li>
<li>Vá em <b>Settings → Pages</b>, escolha a branch <code>main</code> e a pasta <code>/ (root)</code> e salve.</li>
<li>Após alguns minutos, o app fica disponível em <code>https://SEU-USUARIO.github.io/diario-de-bordo/</code>. Compartilhe esse endereço com suas colegas.</li>
</ol>
<p>Para atualizar o app depois, basta substituir o arquivo no repositório.</p>

<h2 id="faq">Perguntas frequentes</h2>
<details><summary>Posso excluir uma turma que não uso mais?</summary><p>Sim, na aba Turmas, com o botão Excluir. O app pede confirmação, e os registros da turma são apagados junto.</p></details>
<details><summary>Meus dados vão para algum servidor?</summary><p>Não. Tudo fica salvo no navegador do seu aparelho.</p></details>
<details><summary>Como levo meu diário para outro aparelho?</summary><p>Use o Backup: copie o código no aparelho antigo e importe no novo.</p></details>
<details><summary>Posso usar no celular e no computador ao mesmo tempo?</summary><p>Sim, mas cada aparelho tem seus próprios dados. Para sincronizar, exporte e importe o código de backup.</p></details>
<details><summary>Fiz uma aula que não estava planejada. Como registro?</summary><p>Na aba Diário, toque em <b>+ Registrar aula</b> e preencha direto.</p></details>

<footer>Diário de Bordo · Manual de uso</footer>
</div></body></html>
