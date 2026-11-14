<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="puuf-xi3u"/><path class="etwk-mefx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:model-monitoring" /></template>
<style>
.etwk-mefx {
  d: path("M5.5 11H8l2 2.5l2.5-7l2 5.5l1.5-2h2.5");
}

.puuf-xi3u {
  d: path("M2.5 3.5h19v13h-19Zm9.5 13v4m-5 0h10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
