<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mk7_uzw9b"/><path class="i6culxb7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:onsite-daycare" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i6culxb7y {
  d: path("m14.5 9.5l2-5C17 3.5 18 3 19 3.25l2.25 2.25c.25.5 0 1.25-.75 1.25h-2l-1.25 3M3 18.5c4 2.5 14 2.5 18 0M8 14l-1.25 5.25M14.5 14l1.25 5.25M6 11l-2.5 2.5");
}

.mk7_uzw9b {
  d: path("M8.25 9.5h6a2.25 2.25 0 0 1 2.25 2.25A2.25 2.25 0 0 1 14.25 14h-6A2.25 2.25 0 0 1 6 11.75A2.25 2.25 0 0 1 8.25 9.5");
}

</style>
