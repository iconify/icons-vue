<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ph4upob6i"/><circle class="zsloapbca"/><path class="pzmpwmb1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:starfish" /></template>
<style>
.ph4upob6i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.92 5.02l1.1 2.11q.92 1.77 2.89 2.1l2.34.39q1.98.33.57 1.76l-1.66 1.69q-1.4 1.43-1.11 3.4l.35 2.35q.3 1.98-1.49 1.08l-2.12-1.06q-1.79-.89-3.58 0L8.09 19.9q-1.79.9-1.49-1.08l.35-2.35q.29-1.97-1.11-3.4l-1.66-1.69q-1.41-1.43.57-1.76l2.34-.39q1.97-.33 2.89-2.1l1.1-2.11q.92-1.77 1.84 0");
}

.pzmpwmb1h {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7.45h.01m5.22 3.8h.01m-2.01 6.15h.01m-6.47 0h.01m-2.01-6.15h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zsloapbca {
  cx: 12px;
  cy: 12.95px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
