<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr41vubrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:temperature-low" /></template>
<style>
.rr41vubrz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13.55V5.5a2.5 2.5 0 0 1 5 0v8.05a4.25 4.25 0 1 1-5 0M7.5 17v-3m10-10.5V20M14 16.5l3.5 3.5l3.5-3.5");
}

</style>
