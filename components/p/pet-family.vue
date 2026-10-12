<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="t6k6kbb4z"/><path class="hxyax1bdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pet-family" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxyax1bdx {
  d: path("M2.75 21.25V15a3.75 3.75 0 0 1 7.5 0v6.25ZM13.25 9l1.5 1.5h2l1.5-1.5v4q0 1.125-.75 1.5q.75.75.75 2.25v4.5h-5v-4.5q0-1.5.75-2.25q-.75-.375-.75-1.5Zm5 11.75h.5a2.5 2.5 0 0 0 2.5-2.5V15.5");
}

.t6k6kbb4z {
  cx: 6.5px;
  cy: 6px;
  r: 2.5px;
}

</style>
