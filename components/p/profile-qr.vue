<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="aq4udkbql"/><rect class="d_88bms5a"/><rect class="sfy9m_bxs"/><path class="s8nsc37xh"/><circle class="zkh97bw0b"/><path class="jw1fev9nb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:profile-qr" /></template>
<style>
.aq4udkbql {
  width: 6.5px;
  height: 6.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.d_88bms5a {
  width: 6.5px;
  height: 6.5px;
  x: 14.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.jw1fev9nb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.25 21.25h5.5a.5.5 0 0 0 .5-.5c0-1.4-1.6-2-3.25-2s-3.25.6-3.25 2a.5.5 0 0 0 .5.5");
}

.s8nsc37xh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 6h.01M18 6h.01M6 18h.01M12 3.75h.01M12 8h.01m-8.26 4h.01M8 12h.01M12 12h.01");
}

.sfy9m_bxs {
  width: 6.5px;
  height: 6.5px;
  x: 2.75px;
  y: 14.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zkh97bw0b {
  cx: 18px;
  cy: 14.75px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
