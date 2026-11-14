<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcqn2ac_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-ice-rink" /></template>
<style>
.dcqn2ac_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3.5H11v7l5.5 1.5a3 3 0 0 1 2.5 3v2H5.5Zm-2 17H18a2.5 2.5 0 0 0 2.5-2.5m-13-1v3.5M16 17v3.5");
}

</style>
