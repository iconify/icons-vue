<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kusr7fjrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:resistor-variable" /></template>
<style>
.kusr7fjrb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h3m0 0L7 11l2.5 6l2.5-6l2.5 6l2.5-6l1.5 3m0 0h3M12 3.5v5m-2-2l2 2l2-2");
}

</style>
