<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bt2bcabgo"/><path class="d0h1ckbhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:merge-sign" /></template>
<style>
.bt2bcabgo {
  d: path("m12 2.5l9.5 17h-19Zm0 6v8");
}

.d0h1ckbhm {
  d: path("M8.5 16.5V15c0-2 3.5-2.5 3.5-4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
