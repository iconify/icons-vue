<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="frdod_ufe"/><circle class="p5v-oc_9l"/><path class="k-swvabop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mantel-clock" /></template>
<style>
.frdod_ufe {
  d: path("M5 19.25v-8a7 7 0 0 1 14 0v8Zm-1.75 0h17.5M7 19.25v2m10-2v2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-swvabop {
  d: path("M12 9.25v2l1.25.75");
}

.p5v-oc_9l {
  cx: 12px;
  cy: 11.25px;
  r: 3.75px;
}

</style>
