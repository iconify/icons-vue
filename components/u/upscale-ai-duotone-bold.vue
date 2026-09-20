<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hr6yi9b8a"/><path class="xtdo68b-f"/><path class="viv5gg8xx"/><path class="jy7vpnbza"/><path class="neof5acyb"/><path class="ld04s_b-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:upscale-ai-duotone-bold" /></template>
<style>
.hr6yi9b8a {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jy7vpnbza {
  d: path("M5 14.5a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2V17a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.ld04s_b-u {
  d: path("M14.5 6H18v3.5");
}

.neof5acyb {
  d: path("m14 10 4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.viv5gg8xx {
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.xtdo68b-f {
  fill: currentColor;
  d: path("M5 14.5a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2V17a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
