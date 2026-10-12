<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="p51kdhlwz"/><path class="chlue9b_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nausea-face" /></template>
<style>
.chlue9b_q {
  d: path("M6.75 10H9m2.5 0h2.25m-7 5.25c.6-.6 1.15-.6 1.75 0s1.15.6 1.75 0s1.15-.6 1.75 0s1.15.6 1.75 0m5.5-12.5c1 1.4 1.75 2.4 1.75 3.4a1.75 1.75 0 0 1-3.5 0c0-1 .75-2 1.75-3.4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p51kdhlwz {
  cx: 10.25px;
  cy: 12.75px;
  r: 7.5px;
}

</style>
