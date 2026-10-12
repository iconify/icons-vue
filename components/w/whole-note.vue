<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z4yjxhb8b"/><path class="bp94v5blq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:whole-note" /></template>
<style>
.bp94v5blq {
  d: path("M9.89 13.77a2.75 1.75-40 1 0 4.22-3.54a2.75 1.75-40 1 0-4.22 3.54");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z4yjxhb8b {
  d: path("M4.5 12a7.5 5.25 0 1 0 15 0a7.5 5.25 0 1 0-15 0");
}

</style>
