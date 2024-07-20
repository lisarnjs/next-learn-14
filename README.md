## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

---

### `<Link>`

After using `<Link>` instead of `<a>`,<br/>
You should now be able to navigate between the pages without seeing a full refresh. Although parts of your application are rendered on the server, there's no full page refresh, making it feel like a web app.

🤫Why is that?

It **Automatic code-splitting and prefetching**! <br/>
Furthermore, in production, whenever `<Link>` components appear in the browser's viewport, Next.js automatically prefetches the code for the linked route in the background. By the time the user clicks the link, the code for the destination page will already be loaded in the background, and this is what makes the page transition near-instant!

> What does Next.js do when a <Link> component appears in the browser’s viewport in a production environment?

**Prefetches the code for the linked route**

Next.js automatically prefetches the code for the linked route in the background. By the time the user clicks the link, the code for the destination page will already be loaded in the background, and this is what makes the page transition near-instant!

**+ Showing active links with `usePathname`**

`usePathname` is a Client Component hook that lets you read the current URL's pathname.

---

### Setting database with postgres

if you're confusing with following [chapter6](https://nextjs.org/learn/dashboard-app/setting-up-your-database), <br/>
I recommend [this blog](https://dev.to/w3tsa/next-js-14-setting-up-your-database-4ank) that has more explanations.

> What is 'seeding' in the context of databases?

**Populating the database with an initial set of data**

Seeding is useful when you want to have some data to work with as you build your application.
