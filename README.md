## Welcome to my GitHub profile :3
> "*The digital world is a bridge between curious hearts, made of bits and love." - @yumekojulia*

```c
/home/juh/C

#include <stdio.h>

typedef struct {
    const char *name;
    const char *role;
    const char *languages[3];
} DevInProgress;

void introduce(DevInProgress me);

int main() {
    DevInProgress me = {
        .name = "Julia",
        .role = "Estudante de ADS, aprendendo programação >.< ",
        .languages = {"pt_BR", "en_US", NULL}
    };

    introduce(me);

    return 0;
}

void introduce(DevInProgress me) {
    printf("👋 Oie! Eu sou a %s!\n", me.name);
    printf("💻 Atualmente: %s\n", me.role);

    printf("🌍 Idiomas: ");
    for (int i = 0; me.languages[i] != NULL; i++) {
        printf("%s ", me.languages[i]);
    }

    printf("\n✨ Obrigada por visitar meu repositório! 💖\n");
}

```

> "*Códigos também são poesia.*" 

<div align="center"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yumekojulia/yumekojulia/output/github-contribution-grid-snake-dark.svg"> <img alt="snake animation" src="https://raw.githubusercontent.com/yumekojulia/yumekojulia/output/github-contribution-grid-snake.svg"> </picture>

<br><br> 

<img loading="lazy" height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yumekojulia&layout=compact&langs_count=7&theme=dracula"/> <img loading="lazy" height="180em" src="https://github-readme-stats.vercel.app/api?username=yumekojulia&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/> </div> 

<div align="center">

### 🌱 I'm always learning
<br>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,github,linux,debian,bash,c,py,ruby,sublime,figma" />
  </a>
</p>

<br>

</div>

<p align="center">
  <a href="https://github.com/yumekojulia/yumekojulia/discussions" style="text-decoration: none;">
    <kbd> 💬 Join the discussion </kbd>
  </a>
</p>



<!--
**yumekojulia/yumekojulia** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
