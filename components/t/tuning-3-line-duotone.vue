<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="h_tsn8bxt"/><circle class="imrhgbc8c"/><circle class="qbe_3qbje"/><path class="gv40cnbhb"/><path class="t0kfsthsf"/><path class="uhbrgbbup"/><path class="zxylmobtl"/><path class="r84xtxbro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tuning-3-line-duotone" /></template>
<style>
.gv40cnbhb {
  d: path("M20 12L20 5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.h_tsn8bxt {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

.imrhgbc8c {
  cx: 20px;
  cy: 14px;
  r: 2px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qbe_3qbje {
  cx: 4px;
  cy: 10px;
  r: 2px;
}

.r84xtxbro {
  d: path("M12 10V5M4 5V7.66667");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.t0kfsthsf {
  d: path("M4 12V19");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.uhbrgbbup {
  d: path("M12 19V14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zxylmobtl {
  d: path("M20 19L20 16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
