<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ra9ls85sm"/><path class="sa7b6bcxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:statement-stamp-duty-paper" /></template>
<style>
.ra9ls85sm {
  d: path("M4.5 2.5h15v19h-15Zm7 3h1m1 0h1m1 0h1m0 1v1m0 1v1");
}

.sa7b6bcxs {
  d: path("M16.5 10.5v.5H16m-1 0h-1m-1 0h-1m-.5-.5v-1m0-1v-1m0-1v-1m-4 1H9m-1.5 8h9m-9 3.5H13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
