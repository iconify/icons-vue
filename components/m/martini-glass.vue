<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kj_mx-nxe"/><circle class="odpsdxyup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:martini-glass" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kj_mx-nxe {
  d: path("M4.25 4.25h15.5q1 0 .29.71l-7.33 7.33q-.71.71-1.42 0L3.96 4.96q-.71-.71.29-.71M12 13v8.25m-3.75 0h7.5");
}

.odpsdxyup {
  cx: 12px;
  cy: 8.25px;
  r: 1.25px;
}

</style>
