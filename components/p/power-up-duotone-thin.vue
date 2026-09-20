<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="um1e2jbde"/><path class="e0b1xgbse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:power-up-duotone-thin" /></template>
<style>
.e0b1xgbse {
  d: path("m16 3 -8 8h5l-9 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.um1e2jbde {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 3 -8 8h5l-9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
