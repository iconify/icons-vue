<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eivsxcrzb"/><path class="jzm-2kbjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-layer-bike" /></template>
<style>
.eivsxcrzb {
  d: path("M2.5 15a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0ZM14 15a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

.jzm-2kbjm {
  d: path("M6.25 15H11l3.75-6.75H9Zm11.5 0l-3-6.75V5.5h2.75M9 8.25L8.5 5.5M7 5.5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
