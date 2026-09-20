<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="og62tq4bb"/><path class="rzbw9hbaj"/><path class="qaw_x5ree"/><path class="hl-uapbht"/><path class="p5dc1z72h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:on-call-duotone-bold" /></template>
<style>
.hl-uapbht {
  d: path("M15 5a3 3 0 0 1 0 6");
}

.og62tq4bb {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.p5dc1z72h {
  d: path("M15 2a6 6 0 0 1 0 12");
}

.qaw_x5ree {
  d: path("M5 17h4");
}

.rzbw9hbaj {
  d: path("M2 5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
