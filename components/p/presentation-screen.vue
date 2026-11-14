<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kekmpcivn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:presentation-screen" /></template>
<style>
.kekmpcivn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 3h12.75A2.625 2.625 0 0 1 21 5.625v6.75A2.625 2.625 0 0 1 18.375 15H5.625A2.625 2.625 0 0 1 3 12.375v-6.75A2.625 2.625 0 0 1 5.625 3M12 15l-5 6.5m5-6.5l5 6.5M12 15v6.5M8 12V9.5m4 2.5V6m4 6V8");
}

</style>
