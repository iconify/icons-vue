<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vr4wc0bze"/><circle class="o5wl3acgc"/><path class="zk-s8gb5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:remix" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o5wl3acgc {
  cx: 10.25px;
  cy: 14.25px;
  r: 1.75px;
}

.vr4wc0bze {
  d: path("M20.25 12a8.25 8.25 0 0 1-14.6 5.25M3.75 12a8.25 8.25 0 0 1 14.6-5.25m.15-3.25v3.25h-3.25M5.5 20.5v-3.25h3.25");
}

.zk-s8gb5o {
  d: path("M12 14.25V8.5l2.75 1");
}

</style>
