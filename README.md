# zeron-omp-acp

Launcher that lets Zeron run a locally installed [Oh My Pi](https://github.com/can1357/oh-my-pi) (`omp`) as an ACP agent.

The release archive contains one script, `omp-acp`, which runs `omp acp`. It uses `$OMP_EXECUTABLE`, then `~/.local/bin/omp`, then `omp` on `PATH`.
