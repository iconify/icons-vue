<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wycc9192d"/><path class="pq-2s6bwa"/><path class="d7n34_2rz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scissor-lift" /></template>
<style>
.d7n34_2rz {
  d: path("M5 3.5h14V6H5Z");
}

.pq-2s6bwa {
  d: path("m14 17l-7-6l7-5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wycc9192d {
  d: path("M6 17h12v3H6Zm1 0l7-6l-7-5.5");
}

</style>
