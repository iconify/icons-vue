<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n9mu2_d4r"/><path class="sturihscz"/><path class="mk93lqrnh"/><path class="hzm2gxbyj"/><path class="ywoqp9dou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:task-merge-outline-bold" /></template>
<style>
.hzm2gxbyj {
  d: path("M17 8v6");
}

.mk93lqrnh {
  d: path("M7 8v6");
}

.n9mu2_d4r {
  d: path("M3 5.5A2.5 2.5 0 0 1 5.5 3h3A2.5 2.5 0 0 1 11 5.5 2.5 2.5 0 0 1 8.5 8h-3A2.5 2.5 0 0 1 3 5.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sturihscz {
  d: path("M13 5.5A2.5 2.5 0 0 1 15.5 3h3A2.5 2.5 0 0 1 21 5.5 2.5 2.5 0 0 1 18.5 8h-3A2.5 2.5 0 0 1 13 5.5");
}

.ywoqp9dou {
  d: path("M3 16.5A2.5 2.5 0 0 1 5.5 14h13a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-13A2.5 2.5 0 0 1 3 16.5");
}

</style>
