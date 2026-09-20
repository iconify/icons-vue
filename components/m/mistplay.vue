<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k2r7bqbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mistplay" /></template>
<style>
.k2r7bqbug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.564 36.83a5.578 5.578 0 1 1-11.156 0a5.578 5.578 0 1 1 11.156 0m-.04-18.123a4.637 4.637 0 1 1-9.273 0a4.637 4.637 0 1 1 9.273 0m-13.496-8.418a3.264 3.264 0 1 1-6.528 0a3.264 3.264 0 0 1 6.528 0M34.27 8.857a3.264 3.264 0 1 1-6.527 0a3.264 3.264 0 1 1 6.528 0m8.229 8.541a3.264 3.264 0 1 1-6.528 0a3.264 3.264 0 0 1 6.528 0m-7.618 9.596a3.591 3.591 0 1 1-7.183 0a3.591 3.591 0 0 1 7.183 0");
}

</style>
