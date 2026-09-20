<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="yfpk0fb4j"/><path class="k0o2zqcoc"/><path class="jx0ofy6bq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rdd-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jx0ofy6bq {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.898 5.817q.151-.376.379-.715h.008a8 8 0 0 0-1.683-.42l1.094 10.066l5.26-4.646l-.15-.463q-.361.185-.75.303q.084.137.143.286a.2.2 0 0 1-.076.252l-.505.354a.24.24 0 0 1-.126.042h-.05a.23.23 0 0 1-.144-.11c-.252-.42-.9-1.49-1.851-2.44a12 12 0 0 0-2.332-1.81a.2.2 0 0 1-.084-.252l.185-.522a.23.23 0 0 1 .11-.126a.19.19 0 0 1 .168 0c.065.021.143.063.235.113q.078.043.17.088m-3.873 12.18l3.4-3.014h.008l-.673-6.128l-6.17 1.953zm-6.001-6.364L4 12.248a7.63 7.63 0 0 0 4.612 7.011l1.179-1.052l-3.493-7.297zm1.048-3.275a7.4 7.4 0 0 0-1.006 2.964l2.105-.674zm7.226-3.711a9 9 0 0 0-.665-.025a7.61 7.61 0 0 0-6.372 3.426l1.204 2.5l6.254-1.995z");
}

.k0o2zqcoc {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.925 19.377a8.6 8.6 0 0 0 1.632.421l-.632-1.313zm8.121-9.813h.084c1.582 0 2.87-1.22 2.87-2.71a2.803 2.803 0 0 0-2.87-2.727a2.81 2.81 0 0 0-2.878 2.626q.832.563 1.548 1.271c.522.522.95 1.102 1.246 1.54M10.91 19.84q.357.036.716.034h.008c.791 0 1.557-.126 2.29-.354l-.455-4.174l-3.3 2.929zm2.829-4.73l.462 4.31v.008a7.626 7.626 0 0 0 4.832-9.006z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yfpk0fb4j {
  fill: var(--svg-color--f5811f, #f5811f);
  d: path("M24 0H0v24h24z");
}

</style>
