<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hhxfk1bfn"/><path class="lwcffhmbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nebula-cloud" /></template>
<style>
.hhxfk1bfn {
  d: path("M6.25 19.5a3.5 3.5 0 1 1 .88-6.89a5 5 0 1 1 9.84-.57a3.75 3.75 0 1 1 .53 7.46Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lwcffhmbs {
  d: path("M12.25 11.75q.27 1.98 2.25 2.25q-1.98.27-2.25 2.25Q11.98 14.27 10 14q1.98-.27 2.25-2.25");
}

</style>
