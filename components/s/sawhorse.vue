<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hnn07w--n"/><path class="y4j3iu7dt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sawhorse" /></template>
<style>
.hnn07w--n {
  width: 18.5px;
  height: 4px;
  x: 2.75px;
  y: 4.75px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y4j3iu7dt {
  d: path("m5.5 8.75l-2.75 12.5M5.5 8.75l2.75 12.5M18.5 8.75l-2.75 12.5m2.75-12.5l2.75 12.5m-14.3-6h10.1");
}

</style>
