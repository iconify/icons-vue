<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dz6gliidf"/><path class="lsg4qfbit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:toothpaste" /></template>
<style>
.dz6gliidf {
  d: path("m2.5 4.5l10 1l2.5 2v3l-2.5 2l-10 1ZM15 7h3.5v4H15ZM5 4.75v8.5");
}

.lsg4qfbit {
  d: path("M18.5 9c3 0 3.25 4.5 0 5.5c-3 1-4 4.5-1 5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
