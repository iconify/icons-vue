<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdhzx5byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:potted-plant-tall" /></template>
<style>
.qdhzx5byn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.097 16h3.806a1.75 1.75 0 0 1 1.722 2.063l-.364 2a1.75 1.75 0 0 1-1.722 1.437h-3.078a1.75 1.75 0 0 1-1.722-1.437l-.364-2A1.75 1.75 0 0 1 10.097 16M12 16V2.5m0 8.5c-3.5 0-6-2-6.5-5c3.5 0 6 2 6.5 5m0 3c3.5 0 6-2 6.5-5c-3.5 0-6 2-6.5 5m0-7.5c2.5 0 4.5-1.5 5-4c-2.5 0-4.5 1.5-5 4");
}

</style>
