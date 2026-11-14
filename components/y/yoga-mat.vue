<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sphh4-u4n"/><path class="rn1l-hf8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:yoga-mat" /></template>
<style>
.rn1l-hf8h {
  d: path("M4.75 9.25c0-5.25 5.5-5.25 5.5 0");
}

.sphh4-u4n {
  d: path("M9 12.25a1.5 1.5 0 0 0-3 0a3 3 0 0 0 6 0a4.5 4.5 0 0 0-9 0a6 6 0 0 0 6 6h12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
