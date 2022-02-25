<h1 align="center">Hi I'm Roman 👋</h1>
<h1 align="center">🖥️ I'm a Software Developer 🖥️</h1>

<p align="center">
  <img src="image/roundedImage01.png"/>
</p>
<br/>

<div align="center">
<h2>✒️ I'm currently learning Blockchain development ✒️</h2>
<h2>📖 I Love to read non-fiction/fiction book 📖</h2>
<h2>⚒️ Currently building: ⚒️</h2>

[<h2>1. R-CLI</h2>](https://github.com/Roman-Ojha/R-CLI)

[<h2>2. MVstreamer</h2>](https://github.com/Roman-Ojha/MVstreamer)

[<h2>3. Social-Application</h2>](https://github.com/Roman-Ojha/Social-Application)

</div>


<h1 align="center"> 📞 Connect with me 📞</h1>

<div align="center">

[<img algin="left" alt="insta" width="45px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Instagram_icon.png/1024px-Instagram_icon.png" target="_blank"/>](https://www.instagram.com/roman__ojha/)
[<img algin="left" alt="Linkdin" width="45px" src="https://cdn-icons-png.flaticon.com/512/174/174857.png" target="_blank"/>](https://www.linkedin.com/in/roman-ojha-3b8bb2209/)
[<img algin="left" alt="Twitter" width="45px" src="https://www.iconpacks.net/icons/2/free-twitter-logo-icon-2429-thumb.png" target="_blank"/>](https://twitter.com/RomanOjha1)
[<img algin="left" alt="Github" width="50px" src="./Icons/github.png" target="_blank"/>](https://github.com/Roman-Ojha)
</div>
<br/>

<h1 align="center">🔥 Technical Skills 🔥</h1>
<div align="center">

[<img algin="left" alt="Html" width="50px" src="./Icons/html.png" target="_blank"/>](https://www.w3schools.com/html/)
[<img algin="left" alt="Css" width="35px" src="./Icons/css.png" target="_blank"/>](https://www.w3schools.com/css/)
[<img algin="left" alt="JS" width="40px" src="./Icons/js.png" target="_blank"/>](https://www.w3schools.com/js/)
[<img algin="left" alt="Node" width="60px" src="./Icons/node.png" target="_blank"/>](https://nodejs.org/en/)
[<img algin="left" alt="React" width="65px" src="./Icons/react.png" target="_blank"/>](https://reactjs.org/)
[<img algin="left" alt="NextJS" width="50px" src="./Icons/nextJS.png" target="_blank"/>](https://nextjs.org/)
[<img algin="left" alt="MongoDB" width="50px" src="./Icons/mongoDB.png" target="_blank"/>](https://www.mongodb.com/)
[<img algin="left" alt="Sass" width="50px" src="./Icons/sass.png" target="_blank"/>](https://sass-lang.com/)
[<img algin="left" alt="Firebase" width="50px" src="./Icons/firebase.png" target="_blank"/>](https://firebase.google.com/)
[<img algin="left" alt="Flutter" width="45px" src="./Icons/flutter.png" target="_blank"/>](https://flutter.dev/)
[<img algin="left" alt="Dart" width="45px" src="./Icons/dart.png" target="_blank"/>](https://dart.dev/)
[<img algin="left" alt="Python" width="45px" src="./Icons/python.png" target="_blank"/>](https://www.python.org/)
[<img algin="left" alt="Django" width="50px" src="./Icons/django.png" target="_blank"/>](https://www.djangoproject.com/)
[<img algin="left" alt="C" width="45px" src="./Icons/c.png" target="_blank"/>](https://www.cprogramming.com/)
[<img algin="left" alt="Cpp" width="45px" src="./Icons/cpp.png" target="_blank"/>](https://www.cprogramming.com/)
[<img algin="left" alt="Docker" width="60px" src="./Icons/docker.png" target="_blank"/>](https://www.docker.com/)
[<img algin="left" alt="snowpack" width="50px" src="./Icons/snowpack.png" target="_blank"/>](https://www.snowpack.dev/)
[<img algin="left" alt="GitHub" width="50px" src="./Icons/github.png" target="_blank"/>](https://github.com/)
[<img algin="left" alt="Figma" width="35px" src="./Icons/figma.svg" style="border-radius:50%" target="_blank"/>](https://www.figma.com/)
[<img algin="left" alt="VScode" width="50px" src="./Icons/vscode.png" style="border-radius:50%" target="_blank"/>](https://code.visualstudio.com/)
[<img algin="left" alt="Notion" width="50px" src="./Icons/notion.png" target="_blank"/>](https://www.notion.so/)

</div>
<br/>

<h2>
<details>
<summary align="center">Dry run and get the desirable output:</summary>

```cpp
struct Node
{
    char value[10];
    struct Node *left;
    struct Node *right;
} * s1, *s2, *s3, *s4;
struct Node *createNode(char value[])
{
    struct Node *n = (struct Node *)malloc(sizeof(struct Node));
    strcpy(n->value, value);
    n->left = NULL;
    n->right = NULL;
    return n;
}
void inOrderTraversal(struct Node *root)
{
    if (root != NULL)
    {
        inOrderTraversal(root->left);
        cout << root->value << " ";
        inOrderTraversal(root->right);
    }
}
int main()
{
    char string[10][10] = {"is", "Another", "Thing", "Random", "Connected", "Every"};
    s1 = createNode(string[0]);
    s2 = createNode(string[2]);
    s3 = createNode(string[4]);
    s4 = createNode(string[5]);
    s1->left = s2;
    s1->right = s3;
    s2->left = s4;
    inOrderTraversal(s1);
    return 0;
};
```
</details>
</h2>
<br/>

<h1 align="center">🎗️ My Profile Info 🎗️</h1>
<div align="center">
    <a href="https://github.com/Roman-Ojha/Roman-Ojha">
        <img title="🔥 Get streak stats for your profile at git.io/streak-stats" alt="Suraj's streak" src="https://github-readme-streak-stats.herokuapp.com/?user=Roman-Ojha&theme=radical&hide_border=true&stroke=0000&background=060A0CD0" width = "100%"/>
    </a>
</div>
<br/>
<div>
 <div align="center">
    <a href="https://github.com/Roman-Ojha/Roman-Ojha"><img alt="Suraj's Top Languages" width="100%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Roman-Ojha&langs_count=8&count_private=true&layout=compact&theme=radical&hide_border=true&bg_color=060A0CD0"/></a>
</div>
<br/>
<div align="center">
    <a href="https://github.com/Roman-Ojha/Roman-Ojha"><img alt="Suraj's Github Stats" width="100%" src="https://github-readme-stats.vercel.app/api?username=Roman-Ojha&theme=radical&hide_border=true&show_icons=true&bg_color=060A0CD0"/></a>
</div>
</div>
<br/>
 <!-- <p align="center">
    <a href="https://github.com/Roman-Ojha/Roman-Ojha"><img alt="Suraj's Activity Graph" src="https://activity-graph.herokuapp.com/graph?username=Roman-Ojha&bg_color=060A0CD0&color=9ce4e0&line=fd428d&point=FFFFFF&hide_border=true" width = "100%" /></a>
</p>
<br/> -->


<!-- test commit to check does conflict happen whiel merging pull request -->