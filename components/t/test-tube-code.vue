<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5rn2sb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:test-tube-code" /></template>
<style>
.m5rn2sb3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3.5V17a2.5 2.5 0 0 0 5 0V3.5M8 3.5h8M5.5 9l-3 3.5l3 3.5m13-7l3 3.5l-3 3.5");
}

</style>
