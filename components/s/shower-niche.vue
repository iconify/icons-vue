<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="t27nvufkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shower-niche" /></template>
<style>
.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.t27nvufkx {
  d: path("M8 16V8.5A1.5 1.5 0 0 1 9.5 7h5A1.5 1.5 0 0 1 16 8.5V16M6 16h12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
