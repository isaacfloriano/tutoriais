# Resolver erro de importação de banco de dados muito grande no PhpMyAdmin
## Neste tutorial estou usando o servior XAMPP

1. Abra o Painel do XAMPP
2. Na linha referente ao Apache clique em **Config** > **PHP (php.ini)**
> Ao abrir o bloco de notas, pressione **Ctrl+F** para abrir a ferramenta de busca.<br>
> Pesquise por **"upload_max_filesize"** sem as aspas, e altere o tamanho para 500M.<br>

**Faça o mesmo processo para:**<br>
* post_max_size=1000M
* memory_limit=512
* max_execution_time=3600

3. Por fim, pressione **Ctrl+S** para salvar as alterações e feche o bloco de notas.

## Pronto! 😎⚡
