<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xi4pb7_rg"/><path class="ahcd83xhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:toggle-left-broken" /></template>
<style>
.ahcd83xhi {
  d: path("M11 12C11 13.6569 9.6569 15 8 15C6.3431 15 5 13.6569 5 12C5 10.3431 6.3431 9 8 9C9.6569 9 11 10.3431 11 12Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xi4pb7_rg {
  d: path("M14 6H16C19.3137 6 22 8.6863 22 12C22 15.3137 19.3137 18 16 18H8C4.6863 18 2 15.3137 2 12C2 8.6863 4.6863 6 8 6H10");
}

</style>
