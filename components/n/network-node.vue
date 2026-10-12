<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="e9-7-8-2z"/><path class="n64rr10zx"/><circle class="jp31ksbuo"/><path class="q_ag9ps7p"/><circle class="lwohrubnq"/><path class="tj0wsc39y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:network-node" /></template>
<style>
.e9-7-8-2z {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jp31ksbuo {
  cx: 18.5px;
  cy: 16px;
  r: 2px;
}

.lwohrubnq {
  cx: 5.5px;
  cy: 16px;
  r: 2px;
}

.n64rr10zx {
  d: path("M12 8.35v-1.6");
}

.q_ag9ps7p {
  d: path("m15.38 14.2l1.38.8");
}

.tj0wsc39y {
  d: path("m8.62 14.2l-1.38.8m5.63-5.75l1.29.75q.87.5.87 1.5V13q0 1-.87 1.5l-1.29.75q-.87.5-1.74 0l-1.29-.75q-.87-.5-.87-1.5v-1.5q0-1 .87-1.5l1.29-.75q.87-.5 1.74 0");
}

</style>
