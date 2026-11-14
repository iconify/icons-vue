<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="znaulxbba"/><path class="na12gss2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-overpay" /></template>
<style>
.na12gss2b {
  d: path("M16 7V4h2v4.75M14.5 15l2.75 3l-2.75 3m3.5-6l2.75 3L18 21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.znaulxbba {
  d: path("M11.16 20.5H4v-10l8-7l8 7v2.54");
}

</style>
