<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w8f78achv"/><path class="fk285acbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:set-square" /></template>
<style>
.fk285acbr {
  d: path("M7.25 12.5V16q0 .75.75.75h3.5q.75 0 .22-.53l-3.94-3.94q-.53-.53-.53.22");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w8f78achv {
  d: path("M3.75 4.75v14q0 1.5 1.5 1.5h14q1.5 0 .44-1.06L4.81 4.31q-1.06-1.06-1.06.44");
}

</style>
