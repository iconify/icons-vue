<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t2wugc77r"/><path class="wg1b7sonh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:planogram" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t2wugc77r {
  d: path("M6 3h12a3.5 3.5 0 0 1 3.5 3.5v11A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5v-11A3.5 3.5 0 0 1 6 3M2.5 9.5h19m-19 5.75h19");
}

.wg1b7sonh {
  d: path("M6.25 5.5zA1.25 1.25 0 0 1 7.5 6.75v1.5A1.25 1.25 0 0 1 6.25 9.5A1.25 1.25 0 0 1 5 8.25v-1.5A1.25 1.25 0 0 1 6.25 5.5m5.25 0H13A1.5 1.5 0 0 1 14.5 7v1A1.5 1.5 0 0 1 13 9.5h-1.5A1.5 1.5 0 0 1 10 8V7a1.5 1.5 0 0 1 1.5-1.5m6.5 1za1 1 0 0 1 1 1v1a1 1 0 0 1-1 1a1 1 0 0 1-1-1v-1a1 1 0 0 1 1-1M6.5 11.75H9a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5H6.5a1.5 1.5 0 0 1-1.5-1.5v-.5a1.5 1.5 0 0 1 1.5-1.5m8.25-.25h2.75A1.5 1.5 0 0 1 19 13v.75a1.5 1.5 0 0 1-1.5 1.5h-2.75a1.5 1.5 0 0 1-1.5-1.5V13a1.5 1.5 0 0 1 1.5-1.5m-8.25 6zA1.5 1.5 0 0 1 8 19v.5A1.5 1.5 0 0 1 6.5 21A1.5 1.5 0 0 1 5 19.5V19a1.5 1.5 0 0 1 1.5-1.5m5.75-.25za1.5 1.5 0 0 1 1.5 1.5v.75a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-.75a1.5 1.5 0 0 1 1.5-1.5m5.5.5zA1.25 1.25 0 0 1 19 19v.75A1.25 1.25 0 0 1 17.75 21a1.25 1.25 0 0 1-1.25-1.25V19a1.25 1.25 0 0 1 1.25-1.25");
}

</style>
