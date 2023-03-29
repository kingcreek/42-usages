# 42-usages

leaks:

atexit(ft_leaks);

void    ft_leaks(void)
{
    system("leaks binary_name");
}



curl -fsSL https://raw.githubusercontent.com/bazuara/42madrid_homebrew_sgoinfre/master/install.sh | zsh




valgrind --leak-check=full ./a.out
