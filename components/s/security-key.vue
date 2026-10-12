<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="lnaguvbtn"/><path class="qxrzjab0q"/><rect class="a5nlw2oyo"/><circle class="exmzjep0j"/><path class="jrdmogvzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:security-key" /></template>
<style>
.a5nlw2oyo {
  width: 11px;
  height: 13.5px;
  x: 6.5px;
  y: 7.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
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

.lnaguvbtn {
  width: 6px;
  height: 5px;
  x: 9px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.qxrzjab0q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 4.75v1m2-1v1");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
