<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="phu67w_rf"/><path class="q2y--hzfq"/><path class="oootd3bay"/><path class="m_-sm9bqc"/><path class="zugrvnb7t"/><path class="a0e2epbbx"/><path class="ltriwmbuu"/><path class="us2evabuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reception-desk-duotone-bold" /></template>
<style>
.a0e2epbbx {
  d: path("M4 13v7h16v-7");
}

.ltriwmbuu {
  d: path("M8 10a4 4 0 0 1 8 0");
}

.m_-sm9bqc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 5.5V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oootd3bay {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 10a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.phu67w_rf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 13h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q2y--hzfq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 13v7h16v-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.us2evabuy {
  d: path("M12 5.5V8");
}

.zugrvnb7t {
  d: path("M2 13h20");
}

</style>
