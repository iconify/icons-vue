<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z5qu6t1sl"/><path class="g6lik9pqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rubber-dam" /></template>
<style>
.g6lik9pqq {
  d: path("M7.75 16.75C7.25 14 6.5 12 6.5 9.5c0-3 1.5-5 3.5-5c.9 0 1.4.75 2 .75s1.1-.75 2-.75c2 0 3.5 2 3.5 5c0 2.5-.75 4.5-1.25 7.25a4.25 1.5 0 0 1-8.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z5qu6t1sl {
  d: path("M7 13.5H4.5l-2 6.5h17l2-6.5H17");
}

</style>
