<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oypzkhe7l"/><path class="g1eyjub-w"/><path class="t7j7uj08u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soccer-net-goal" /></template>
<style>
.g1eyjub-w {
  d: path("M7.5 14a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oypzkhe7l {
  d: path("M3 20V5h18v15");
}

.t7j7uj08u {
  d: path("m12.9 12.675l.246.184a1.425 1.425 0 0 1 .479 1.641l-.01.027a1.5 1.5 0 0 1-1.405.973h-.42a1.5 1.5 0 0 1-1.405-.973l-.01-.027a1.425 1.425 0 0 1 .479-1.641l.246-.184a1.5 1.5 0 0 1 1.8 0M12 12V9.5m2 4l2.25-1m-3 3l1.5 2.25m-4-2.25l-1.5 2.25M10 13.5l-2.25-1");
}

</style>
