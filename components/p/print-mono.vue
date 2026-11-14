<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6qrc6bvk"/><path class="qmmselt1q"/><path class="mxiu0ebpx"/><path class="nwq383cjt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:print-mono" /></template>
<style>
.e6qrc6bvk {
  d: path("M7 6.5v-4h10v4M6 16H4.5a2 2 0 0 1-2-2V8.5a2 2 0 0 1 2-2h15a2 2 0 0 1 2 2V14a2 2 0 0 1-2 2H18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mxiu0ebpx {
  d: path("M9.75 16.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.nwq383cjt {
  fill: currentColor;
  d: path("M12 14.25a2.25 2.25 0 0 1 0 4.5Z");
}

.qmmselt1q {
  d: path("M7.75 11.5h8.5A1.75 1.75 0 0 1 18 13.25v6.5a1.75 1.75 0 0 1-1.75 1.75h-8.5A1.75 1.75 0 0 1 6 19.75v-6.5a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
