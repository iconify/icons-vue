<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lptewns2i"/><path class="gza-m1bif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ski-bike" /></template>
<style>
.gza-m1bif {
  d: path("M13.5 19H20a2 2 0 0 0 2-2");
}

.lptewns2i {
  d: path("m5 19l3.5-8.5H15l2.5 8.5m-9-8.5v-3m-1.75 0h4m4.25 3L14 6h3M2.5 19H8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
