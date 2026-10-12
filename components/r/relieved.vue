<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="q0zlp8b_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:relieved" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q0zlp8b_q {
  d: path("M7.75 10.25c.6.75 1.9.75 2.5 0m3.5 0c.6.75 1.9.75 2.5 0m-9-2.75c.8-.6 2-.75 3-.25m6.5.25c-.8-.6-2-.75-3-.25m-4.25 8c.7.65 1.55 1 2.5 1s1.8-.35 2.5-1");
}

</style>
