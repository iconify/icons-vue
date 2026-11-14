<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r1ynpub7t"/><path class="qahig3lrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:portable-compressor" /></template>
<style>
.qahig3lrf {
  d: path("M5.75 14a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM9 14l1.5-1.5");
}

.r1ynpub7t {
  d: path("M2.5 7.5h13v13h-13Zm3.5 0v-3h6v3m3.5 8.5c6 0 6-6.5 3-6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
