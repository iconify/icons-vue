<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sgjbtc6qp"/><path class="tjiinjgmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:marshmallow-cocoa" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sgjbtc6qp {
  d: path("M4.5 8h11v9a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 17Zm11 2H17a2.5 2.5 0 0 1 0 5h-1.5");
}

.tjiinjgmo {
  d: path("M8 5.25h.25A1.75 1.75 0 0 1 10 7v.25A1.75 1.75 0 0 1 8.25 9H8a1.75 1.75 0 0 1-1.75-1.75V7A1.75 1.75 0 0 1 8 5.25m4.5-.75h.25a1.75 1.75 0 0 1 1.75 1.75v.25a1.75 1.75 0 0 1-1.75 1.75h-.25a1.75 1.75 0 0 1-1.75-1.75v-.25A1.75 1.75 0 0 1 12.5 4.5");
}

</style>
