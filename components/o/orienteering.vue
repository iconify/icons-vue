<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r8pdbsjxx"/><path class="s6m0au_2x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:orienteering" /></template>
<style>
.r8pdbsjxx {
  d: path("M14.197 18.683L13.5 19L8 16.5L2.5 19V5.5L8 3l5.5 2.5L19 3v8.775M8 3v13.5m5.5-11V16m0 .4V19M5.25 8h.01m5.49 3h.01");
}

.s6m0au_2x {
  d: path("M17 21v-7l4 1.75l-4 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
