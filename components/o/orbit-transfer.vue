<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="peiq2hfxm"/><path class="cq61gq66i"/><path class="w526dfbhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:orbit-transfer" /></template>
<style>
.cq61gq66i {
  d: path("M16.5 12a4.5 4.5 0 1 0-7.68 3.18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.peiq2hfxm {
  cx: 12px;
  cy: 12px;
  r: 1.75px;
}

.w526dfbhz {
  d: path("M3.31 8.84a9.25 9.25 0 0 1 17.38 0M16.5 12a6.875 6.45 0 0 1-13.75 0");
}

</style>
