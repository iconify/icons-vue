<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oelioormc"/><path class="iz-cakr7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:room-service-cart" /></template>
<style>
.iz-cakr7o {
  d: path("M4 20a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm13 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.oelioormc {
  d: path("M12 3.5V6m-5.5 5.5a5.5 5.5 0 0 1 11 0M3 11.5h18m-15.5 0v7h13v-7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
