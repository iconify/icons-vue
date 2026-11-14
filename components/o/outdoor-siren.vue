<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjws-xr1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:outdoor-siren" /></template>
<style>
.gjws-xr1m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 17v-4a5 5 0 0 1 10 0v4M4.5 17h15v4h-15ZM12 2.5V5M4 6l1.75 1.75M20 6l-1.75 1.75");
}

</style>
