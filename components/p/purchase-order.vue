<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sf1l1xb4k"/><path class="dhnis08of"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:purchase-order" /></template>
<style>
.dhnis08of {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-11 3.5h3.5M8.25 15h2.5m3.75-1h6l.75 7.25h-7.5Zm1.25 0v-.75a1.75 1.75 0 0 1 3.5 0V14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sf1l1xb4k {
  d: path("M10.5 21.25H7.25a2.5 2.5 0 0 1-2.5-2.5V5.25a2.5 2.5 0 0 1 2.5-2.5h6.5l5.5 5.5");
}

</style>
