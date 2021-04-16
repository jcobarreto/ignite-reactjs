<h1 align="center">
  Next.js & JAMStack
</h1>

<p align="center">
  <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-use">How To Use</a>
</p>

<p align="center">
  <img alt="ignews" src="https://github.com/jcobarreto/ignite-reactjs/blob/main/03-ignews/.github/ignews.png">
</p>

## 💬 Project

In this module we will understand how Next.js transforms our way of developing front-end applications and we will discover important concepts like SSR and SSG.
Also, how the front-end has been transformed in recent years with the possibility of having back-end functions (serverless) running in a front-end environment.
Finally, it is very common to develop front-end applications that are not connected to a single back-end today, so here we will understand the concept of JAMStack and how to connect our front-end with a CMS.

## 🚀 Technologies

Project developed with the following technologies:

- [Create Next App](https://nextjs.org/docs/api-reference/create-next-app)
- [React](https://reactjs.org)
- [TypeScript](https://www.typescriptlang.org/)
- [SASS](https://sass-lang.com/)
- [Stripe](https://stripe.com/en-br)
- [NextAuth.js](https://next-auth.js.org/)
- [FaunaDB](https://fauna.com/)
- [Prismic CMS](https://prismic.io/)

## 🔖 Layout

You can view the layout of the project in the [web](https://www.figma.com/file/uaTSqvL5NdaczciSXPLFhi/ig.news?node-id=0%3A1) version. You need to have a [Figma](https://www.figma.com/) account to access it.

## ℹ️ How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Yarn](https://legacy.yarnpkg.com). From your command line:

```bash
# Clone the repository
$ git clone https://github.com/jcobarreto/ignite-reactjs.git

# Go into the directory
$ cd 03-ignews

# Install dependencies
$ yarn

# Run the stripe listener
$ stripe listen --forward-to localhost:3000/api/webhooks

# Run the development server
$ yarn dev

# Navigate to http://localhost:3000
# The app will automatically reload if you change any of the source files.
```
