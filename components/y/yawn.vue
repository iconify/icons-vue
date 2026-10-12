<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="yv3j-iizx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:yawn" /></template>
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

.yv3j-iizx {
  d: path("M7.5 9.5c.75.6 2 .6 2.75 0m3.5 0c.75.6 2 .6 2.75 0M12 13c1.65 0 2.75 1.3 2.75 2.9s-1.1 2.85-2.75 2.85s-2.75-1.25-2.75-2.85S10.35 13 12 13");
}

</style>
