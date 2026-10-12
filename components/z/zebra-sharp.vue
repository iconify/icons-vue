<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jiax8abec"/><path class="dj249704j"/><path class="viu3swbad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zebra-sharp" /></template>
<style>
.dj249704j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 7.75l2.5 1.5l2.5-1.5m-7.4 3.5c1.75 0 3.25.5 4.9 1.5c1.65-1 3.15-1.5 4.9-1.5m-8.5 3.5h2.133l1.467 1l1.467-1H15.6");
}

.jiax8abec {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.25h1.65l1.35.6L18.25 3c.4 1.6 0 3.4-1.2 4.6l.45 1.2v1.45c0 2.1-.85 3.6-1.5 5.5V17a4 4 0 0 1-8 0v-1.25c-.65-1.9-1.5-3.4-1.5-5.5V8.8l.45-1.2c-1.2-1.2-1.6-3-1.2-4.6L9 5.85l1.35-.6z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.viu3swbad {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 18.5h.01m3.49 0h.01");
}

</style>
