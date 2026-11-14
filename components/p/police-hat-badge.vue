<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fw83uhd5n"/><path class="eujasdjuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:police-hat-badge" /></template>
<style>
.eujasdjuy {
  d: path("m12.382 6.599l.03.067a1.5 1.5 0 0 0 1.205.875l.073.008a.419.419 0 0 1 .236.727l-.054.049a1.5 1.5 0 0 0-.46 1.417l.014.071a.419.419 0 0 1-.618.449l-.063-.036a1.5 1.5 0 0 0-1.49 0l-.063.036a.419.419 0 0 1-.618-.449l.014-.071a1.5 1.5 0 0 0-.46-1.417l-.054-.049a.419.419 0 0 1 .236-.727l.073-.008a1.5 1.5 0 0 0 1.205-.875l.03-.067a.419.419 0 0 1 .764 0");
}

.fw83uhd5n {
  d: path("M3.5 9.5c0-3.5 3.75-6 8.5-6s8.5 2.5 8.5 6L18 13H6ZM6 16h12c-1 3.5-11 3.5-12 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
