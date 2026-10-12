<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="up5bnccaf"/><path class="h64i6254i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pv-cell" /></template>
<style>
.h64i6254i {
  d: path("M9.5 5H11M5 9.5V11m3.18-2.82l1.06 1.06m.51 3.01H20.5q.75 0 .43.68l-2.11 4.39q-.32.68-1.07.68H7q-.75 0-.43-.68l2.11-4.39q.32-.68 1.07-.68m5.38 0L12.38 18m-4.75-2.87h12.24M12.38 18v3.25m-3.25 0h6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.up5bnccaf {
  cx: 5px;
  cy: 5px;
  r: 2.25px;
}

</style>
