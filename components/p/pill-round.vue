<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nbsc7db3a"/><path class="qjg_o9u4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pill-round" /></template>
<style>
.nbsc7db3a {
  d: path("M3 10a9 4 0 1 0 18 0a9 4 0 1 0-18 0Z");
}

.qjg_o9u4m {
  d: path("M3 10v4a9 4 0 0 0 18 0v-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
