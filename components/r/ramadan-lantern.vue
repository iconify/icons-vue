<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p12k4uybo"/><path class="ggl-3cbih"/><rect class="k3kcb6tzu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ramadan-lantern" /></template>
<style>
.ggl-3cbih {
  d: path("M10 16.5V13a2 2 0 0 1 4 0v3.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k3kcb6tzu {
  width: 13.5px;
  height: 2.25px;
  x: 5.25px;
  y: 19px;
  rx: 0.75px;
}

.p12k4uybo {
  d: path("M12 5V2.75M8.5 8.5a3.5 3.5 0 0 1 7 0Zm.25 0h6.5q.75 0 1.2.6l.6.8q.45.6.45 1.35v7q0 .75-.75.75h-9.5q-.75 0-.75-.75v-7q0-.75.45-1.35l.6-.8q.45-.6 1.2-.6");
}

</style>
