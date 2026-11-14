<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qyv03sbyd"/><path class="osiuk4zty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reception-sofa" /></template>
<style>
.osiuk4zty {
  d: path("M2.5 20v-5.5a1.25 1.25 0 0 1 2.5 0v2h8v-2a1.25 1.25 0 0 1 2.5 0V20ZM19.75 8v13.5M18 8h3.5l-1-4.5H19Zm0 13.5h3.5");
}

.qyv03sbyd {
  d: path("M4 13.5v-2a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
