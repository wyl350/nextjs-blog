This is a starter template for [Learn Next.js](https://nextjs.org/learn).


## getStaticProps 

This is possible because getStaticProps only runs on the server-side. It will never run on the client-side. It won’t even be included in the JS bundle for the browser. That means you can write code such as direct database queries without them being sent to browsers.

## getServerSideProps 

To use Server-side Rendering, you need to export getServerSideProps instead of getStaticProps from your page.

## ServerLess Functions 

地址 : https://zhuanlan.zhihu.com/p/99175443

