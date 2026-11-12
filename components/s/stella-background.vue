<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="utbt8yb3k"/><path class="fgzwvybdy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stella-background" /></template>
<style>
.fgzwvybdy {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.43 5C17.505 5 20 7.476 20 10.532a5.5 5.5 0 0 1-1.463 3.736a5.6 5.6 0 0 1-2.424 1.538l-.02.005q-.212.067-.428.115L4.204 18.994c-.146.039-.261-.125-.174-.247l3.387-4.764a.161.161 0 0 0-.162-.251l-2.566.485c-.148.028-.251-.142-.156-.258l5.188-6.386a5.6 5.6 0 0 1 2.027-1.892A5.55 5.55 0 0 1 14.43 5m-.208 4.156L11.82 8.048l.753 2.52l-3.233 4.403l4.657-2.765l2.4 1.106l-.751-2.52l1.51-2.744z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.utbt8yb3k {
  fill: var(--svg-color--6a81ff, #6a81ff);
  d: path("M24 0H0v24h24z");
}

</style>
