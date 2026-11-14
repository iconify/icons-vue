<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n3o-vs7xv"/><path class="htts0xb3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tennis-deuce" /></template>
<style>
.htts0xb3t {
  d: path("M3.75 5.25a3.25 3.25 0 0 1 0 5.5m16.5-5.5a3.25 3.25 0 0 0 0 5.5M8 17h8m-8 3h8");
}

.n3o-vs7xv {
  d: path("M2.5 8a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm11 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
