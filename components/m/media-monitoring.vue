<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qflg01q3e"/><path class="krdrgcbvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:media-monitoring" /></template>
<style>
.krdrgcbvl {
  d: path("M6 10h2.5l2-3l2.5 6l2-3h3");
}

.qflg01q3e {
  d: path("M2.5 3.5h19v13h-19Zm9.5 13v4m-3.5 0h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
