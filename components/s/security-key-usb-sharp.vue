<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="adga_ub8b"/><circle class="exmzjep0j"/><path class="jrdmogvzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:security-key-usb-sharp" /></template>
<style>
.adga_ub8b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.75h6v5H9zm2 2v1m2-1v1m-6.5 2h11v13.5h-11z");
}

.exmzjep0j {
  cx: 12px;
  cy: 13px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jrdmogvzn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
