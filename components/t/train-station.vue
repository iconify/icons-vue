<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sztz8rboh"/><circle class="xhuo7yavf"/><path class="k2s5fpbss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:train-station" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2s5fpbss {
  d: path("M9 21.25v-3.5a3 3 0 0 1 6 0v3.5M5.25 15v3m13.5-3v3");
}

.sztz8rboh {
  d: path("M2.75 20.75V12.5q0-.5.5-.5h4q.5 0 .5-.5V7q0-.5.37-.83l3.51-3.09q.37-.33.74 0l3.51 3.09q.37.33.37.83v4.5q0 .5.5.5h4q.5 0 .5.5v8.25q0 .5-.5.5H3.25q-.5 0-.5-.5");
}

.xhuo7yavf {
  cx: 12px;
  cy: 8.75px;
  r: 1.75px;
}

</style>
