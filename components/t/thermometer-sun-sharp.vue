<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tk4jbcb3k"/><circle class="tahfobaab"/><path class="fsgl9pbbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thermometer-sun-sharp" /></template>
<style>
.fsgl9pbbl {
  d: path("m12.67 5.42l-.71-.71m3.54-.46v-1m2.83 2.17l.71-.71m.46 3.54h1m-2.17 2.83l.71.71m-3.54.46v1");
}

.tahfobaab {
  cx: 15.5px;
  cy: 8.25px;
  r: 2.5px;
}

.tk4jbcb3k {
  d: path("M5 15.45V3.85h4v11.6a3.25 3.25 0 1 1-4 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
