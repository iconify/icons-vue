<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="t2b2_1b6m"/><path class="lbknmcbqn"/><circle class="har4go24q"/><path class="npjwj4b2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:piston" /></template>
<style>
.har4go24q {
  cx: 12px;
  cy: 18.75px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lbknmcbqn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 5.75h11M6.5 8h11M12 11.75v4.5");
}

.npjwj4b2p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18.75h.01");
}

.t2b2_1b6m {
  width: 11px;
  height: 9px;
  x: 6.5px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
