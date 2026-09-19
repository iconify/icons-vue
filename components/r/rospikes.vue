<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="woq2rubuz"/><circle class="w9nxh5bkg"/><path class="p083q4x9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rospikes" /></template>
<style>
.p083q4x9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.387 17.833h-8.122V9.711c0-2.306-1.905-4.211-4.211-4.211h-3.911c-2.306 0-4.211 1.905-4.211 4.211v8.122H9.71c-2.307 0-4.212 1.905-4.212 4.212v3.91c0 2.307 1.905 4.212 4.212 4.212h8.121v8.122c0 2.306 1.906 4.211 4.212 4.211h3.91c2.307 0 4.212-1.905 4.212-4.211v-8.122h8.122c2.306 0 4.211-1.905 4.211-4.212v-3.91c.1-2.306-1.805-4.212-4.11-4.212Z");
}

.w9nxh5bkg {
  cx: 24.048px;
  cy: 24.05px;
  r: 3.51px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.woq2rubuz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.756 12.519l-2.708-2.707l-2.707 2.707m5.415 23.062l-2.708 2.708l-2.707-2.708m14.238-8.823l2.708-2.708l-2.708-2.707m-23.062 5.415L9.81 24.05l2.707-2.707");
}

</style>
