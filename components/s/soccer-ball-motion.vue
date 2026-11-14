<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cqld81biz"/><path class="kt2lx7i9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soccer-ball-motion" /></template>
<style>
.cqld81biz {
  d: path("M8 12a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kt2lx7i9l {
  d: path("m15.9 9.425l1.29.967a1.5 1.5 0 0 1 .549 1.587l-.442 1.657a1.5 1.5 0 0 1-1.449 1.114h-1.696a1.5 1.5 0 0 1-1.449-1.114l-.442-1.657a1.5 1.5 0 0 1 .549-1.587l1.29-.967a1.5 1.5 0 0 1 1.8 0M15 8.75V5m3 6l3.75-1.25m-4.75 5l2 3m-6-3l-2 3M12 11L8.25 9.75m-6 2.25h3M3 16h3");
}

</style>
