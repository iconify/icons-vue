<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wb-3accoe"/><path class="viv8vacgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smartphone-cracked" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.viv8vacgu {
  d: path("m15 2.5l-2.5 5l2 3L11 16m1.5-8.5L9 8.5");
}

.wb-3accoe {
  d: path("M6 2.5h12v19H6ZM10.5 18h3");
}

</style>
