<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="gmx6obc6f"/><circle class="zsloapbca"/><path class="pzmpwmb1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:starfish-sharp" /></template>
<style>
.gmx6obc6f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.92 5.02l1.1 2.11l.92 1.77l1.97.33l2.34.39l1.98.33l-1.41 1.43l-1.66 1.69l-1.4 1.43l.29 1.97l.35 2.35l.3 1.98l-1.79-.9l-2.12-1.06l-1.79-.89l-1.79.89l-2.12 1.06l-1.79.9l.3-1.98l.35-2.35l.29-1.97l-1.4-1.43l-1.66-1.69l-1.41-1.43l1.98-.33l2.34-.39l1.97-.33l.92-1.77l1.1-2.11l.92-1.77z");
}

.pzmpwmb1h {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7.45h.01m5.22 3.8h.01m-2.01 6.15h.01m-6.47 0h.01m-2.01-6.15h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zsloapbca {
  cx: 12px;
  cy: 12.95px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
