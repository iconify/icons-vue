<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c05zqobhe"/><path class="xapqp6brg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mppt" /></template>
<style>
.c05zqobhe {
  d: path("M6.866 2.5h10.268a1.75 1.75 0 0 1 1.697 1.326l1.625 6.5a1.75 1.75 0 0 1-1.697 2.174H5.241a1.75 1.75 0 0 1-1.697-2.174l1.625-6.5A1.75 1.75 0 0 1 6.866 2.5M12 2.5v10m-7.75-5h15.5m-11.25 5v8m-3 0h6m3 1L17 19l1.5 1.5l3-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xapqp6brg {
  d: path("M18.5 17.5h3v3");
}

</style>
