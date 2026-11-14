<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b8mr1nbpn"/><path class="d4nw0_bhx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tiki-mug" /></template>
<style>
.b8mr1nbpn {
  d: path("M6.5 4.5H13A3.5 3.5 0 0 1 16.5 8v8a3.5 3.5 0 0 1-3.5 3.5H6.5A3.5 3.5 0 0 1 3 16V8a3.5 3.5 0 0 1 3.5-3.5m10 3.5H18a2.5 2.5 0 0 1 2.5 2.5V13a2.5 2.5 0 0 1-2.5 2.5h-1.5m-10.75-6h2.5m3 0h2.5");
}

.d4nw0_bhx {
  d: path("M6 14.5L7.75 16l1.75-1.5l1.75 1.5L13 14.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
