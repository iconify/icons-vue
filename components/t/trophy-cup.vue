<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k1t9pbnwp"/><path class="z1-apxm4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:trophy-cup" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k1t9pbnwp {
  d: path("M7 3h10v5.5a5 5 0 0 1-10 0Z");
}

.z1-apxm4w {
  d: path("M7 5H4v2a3 3 0 0 0 3.25 3M17 5h3v2a3 3 0 0 1-3.25 3M12 13.5v4m-2.25 0h4.5A1.75 1.75 0 0 1 16 19.25A1.75 1.75 0 0 1 14.25 21h-4.5A1.75 1.75 0 0 1 8 19.25a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
