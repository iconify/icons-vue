<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="wxsbgrr5t"/><path class="pnn7bwp7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pool-ball" /></template>
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

.pnn7bwp7y {
  d: path("M12 8.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 1 0 0-3m0 3a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 1 0 0-3.5");
}

.wxsbgrr5t {
  d: path("M12 5.75a6.25 6.25 0 1 0 0 12.5a6.25 6.25 0 1 0 0-12.5");
}

</style>
