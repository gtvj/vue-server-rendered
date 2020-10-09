# Trying Vue.js server rendering

Simple server-rendered Vue.js. As the [Vue.js Server Rendering Guide](https://ssr.vuejs.org) says:

<blockquote cite="https://ssr.vuejs.org/#what-is-server-side-rendering-ssr">
it is also possible to render the same components into HTML strings on the server, send them directly to the browser, and finally "hydrate" the static markup into a fully interactive app on the client.
A server-rendered Vue.js app can also be considered "isomorphic" or "universal", in the sense that the majority of your app's code runs on both the server and the client.
</blockquote>

The question is, unless you're going for the 'hydration' approach (which isn't progressive enhancement), what is Vue.js really bringing? You could do all of this more simply with Express. 
