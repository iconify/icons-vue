<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhgtjsbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spikeball" /></template>
<style>
.dhgtjsbki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 16a9.25 4 0 1 0 18.5 0a9.25 4 0 1 0-18.5 0M9 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0M2.75 16h18.5M12 12v8");
}

</style>
