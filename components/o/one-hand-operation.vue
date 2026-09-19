<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yxvxsmv3w"/><path class="o1saloawr"/><circle class="mq0t-vbpo"/><circle class="u7r9ppb7d"/><circle class="y3t70ebja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:one-hand-operation" /></template>
<style>
.mq0t-vbpo {
  cx: 26.47px;
  cy: 19.198px;
  r: 0.75px;
  fill: currentColor;
}

.o1saloawr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.1 33.87H13.062a2.307 2.307 0 0 1-2.307-2.308V6.807A2.307 2.307 0 0 1 13.062 4.5h15.44a2.307 2.307 0 0 1 2.307 2.307v22.658M10.755 8.672h20.054M10.755 29.697h11.187");
}

.u7r9ppb7d {
  cx: 22.832px;
  cy: 19.198px;
  r: 0.75px;
  fill: currentColor;
}

.y3t70ebja {
  cx: 19.195px;
  cy: 19.198px;
  r: 0.75px;
  fill: currentColor;
}

.yxvxsmv3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.809 29.465c-2.362-.033-3.203-1.03-5.434-4.005s-4.618-2.836-5.434-1.941c-.68.744 3.331 9.477 4.528 10.868a19.5 19.5 0 0 0 1.844 1.94s-.043 4.165-.172 7.173m11.104-.736a75 75 0 0 1-1.132-7.827c.065-.324.025-4.658-.004-5.693s-1.128-9.768-1.872-11.418s-3.428-3.817-3.428-3.817");
}

</style>
