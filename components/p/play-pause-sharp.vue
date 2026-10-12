<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yux0r_brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:play-pause-sharp" /></template>
<style>
.yux0r_brr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.48 6.61l6.54 4.53l1.23.86l-1.23.86l-6.54 4.53l-1.23.86V5.75zm11.27-.86v12.5m4.5-12.5v12.5");
}

</style>
