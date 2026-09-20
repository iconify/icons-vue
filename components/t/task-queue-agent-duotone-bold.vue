<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n-66l9bfk"/><path class="bfzmo4bxd"/><path class="ble2d-bci"/><path class="slmpunbln"/><path class="eh4_3ebbt"/><path class="w57l-wb8f"/><path class="v_i-xnbbq"/><path class="oa7ibkb8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:task-queue-agent-duotone-bold" /></template>
<style>
.bfzmo4bxd {
  fill: currentColor;
  d: path("M10 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ble2d-bci {
  fill: currentColor;
  d: path("M16 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.eh4_3ebbt {
  d: path("M4 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.n-66l9bfk {
  fill: currentColor;
  d: path("M4 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.oa7ibkb8p {
  d: path("M14.32 10a5.5 5.5 0 1 1 -4.64 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.slmpunbln {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14.32 10a5.5 5.5 0 1 1 -4.64 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v_i-xnbbq {
  d: path("M16 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.w57l-wb8f {
  d: path("M10 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
