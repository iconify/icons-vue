<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l1mthztqi"/><path class="a_x_xwdfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:railway-crossing" /></template>
<style>
.a_x_xwdfn {
  d: path("M10.75 11.5h2.5a1 1 0 0 1 1 1v4.25h-4.5V12.5a1 1 0 0 1 1-1m-1 2.5h4.5m-4 4.25l.5-1.5m3 1.5l-.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l1mthztqi {
  d: path("m12.98 4.99l7.29 13.02q.98 1.74-1.02 1.74H4.75q-2 0-1.02-1.74l7.29-13.02q.98-1.74 1.96 0");
}

</style>
