<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rknchmb5r"/><path class="qcw_mabaa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-moderator" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qcw_mabaa {
  d: path("M4 20.25h11a.75.75 0 0 0 .75-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5a.75.75 0 0 0 .75.75M16.25 6.5h4.5a.4.4 0 0 1 .35.6L20 9l1.1 1.9a.4.4 0 0 1-.35.6h-4.5Zm0 5V15");
}

.rknchmb5r {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
}

</style>
