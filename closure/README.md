# [Closure](https://github.com/hchiam/learning-closure)

<https://github.com/hchiam/learning-closure>

## These don't seem to be working:

<https://github.com/thanpolas/generator-closure>

```bash
mkdir my-app && cd my-app
npm install -g generator-closure
yo closure
```

I keep getting "primordials is not defined". Same with this:

<https://github.com/andrewpmckenzie/generator-closure-stack>

```bash
mkdir my-app && cd my-app && yarn add grunt && yarn global add generator-closure-stack grunt && yo closure-stack && grunt setup && grunt run:dev
```

Do you need to `git clone https://github.com/google/closure-library app/closure-library` ?

```bash
cd my-app
grunt run:dev
```
