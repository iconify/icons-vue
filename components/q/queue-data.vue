<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijzd0lqcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:queue-data" /></template>
<style>
.ijzd0lqcg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.25 5h5v5h-5ZM9.5 5h5v5h-5Zm7.25 0h5v5h-5ZM2.5 16h19m-3-3l3 3l-3 3");
}

</style>
