<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sflp0cenm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tunnel-cross-section" /></template>
<style>
.sflp0cenm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17v-7a6.5 6.5 0 0 1 13 0v7Zm0 2.75v2m0-1h13m0-1v2M18.75 3.5h2.5M20 3.5V17m-1.25 0h2.5");
}

</style>
