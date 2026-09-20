<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cn37tab9x"/><path class="ix782hbkz"/><path class="p-3tqnbzb"/><path class="q747pdnhy"/><path class="r5fo3gbwg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:router-outline-bold" /></template>
<style>
.cn37tab9x {
  d: path("M2 11a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.ix782hbkz {
  d: path("M5 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.p-3tqnbzb {
  d: path("M9 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.q747pdnhy {
  d: path("M7 9 4 6");
}

.r5fo3gbwg {
  d: path("m17 9 3 -3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
