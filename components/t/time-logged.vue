<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n5cg660mb"/><path class="d1na1ubeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:time-logged" /></template>
<style>
.d1na1ubeq {
  d: path("M8 6.5h8v2H8Zm0 4.75h6v2H8ZM10.8 18H8v-2h3.5v1.3m3.25.7l2 2L21 15.75");
}

.n5cg660mb {
  d: path("M14.3 21.5H4.5v-19h15v10.8m0 7.9v.3h-.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
