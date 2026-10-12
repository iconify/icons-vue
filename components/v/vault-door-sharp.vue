<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="yoci39b4r"/><circle class="ctk1fcczq"/><path class="pc-b8disp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vault-door-sharp" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ctk1fcczq {
  cx: 12px;
  cy: 12px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pc-b8disp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.25v-3.5m0 9v3.5M9.25 12h-3.5m9 0h3.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yoci39b4r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.95 16.95h.01m-9.91 0h.01m-.01-9.9h.01m9.89 0h.01");
}

</style>
