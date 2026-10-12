<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q3c5rrbpr"/><path class="zo2y3ziru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:siem-dashboard" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q3c5rrbpr {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 3.25px;
  rx: 2.25px;
}

.zo2y3ziru {
  d: path("M12 16.75v4.5m-3.5 0h7M6 12.5l3-3.25l2.5 2l3-4l3.5 3");
}

</style>
