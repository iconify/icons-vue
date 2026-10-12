<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v9bvazb-w"/><circle class="w-rip4ezp"/><path class="oxb3rggdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sea-turtle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oxb3rggdi {
  d: path("M12 7a5 6.5 0 0 1 5 6.5a5 6.5 0 0 1-5 6.5a5 6.5 0 0 1-5-6.5A5 6.5 0 0 1 12 7m0 3v7");
}

.v9bvazb-w {
  d: path("M6.94 10L3.87 7.5q-.62-.5-.76.29l-.22 1.17q-.14.79.53 1.22l2.97 1.89q.67.43.86-.35l.12-.44q.19-.78-.43-1.28m10.12 0l3.07-2.5q.62-.5.76.29l.22 1.17q.14.79-.53 1.22l-2.97 1.89q-.67.43-.86-.35l-.12-.44q-.19-.78.43-1.28m-9.94 6.9l-2.43 2.2q-.44.4.14.53l2.09.49q.58.13.94-.35l.58-.79q.36-.48.04-.99l-.6-.98q-.32-.51-.76-.11m9.76 0l2.43 2.2q.44.4-.14.53l-2.09.49q-.58.13-.94-.35l-.58-.79q-.36-.48-.04-.99l.6-.98q.32-.51.76-.11");
}

.w-rip4ezp {
  cx: 12px;
  cy: 5.25px;
  r: 1.75px;
}

</style>
