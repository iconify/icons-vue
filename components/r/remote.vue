<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ysqkh55uc"/><circle class="zz9p51bci"/><path class="l57ozh_fr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:remote" /></template>
<style>
.l57ozh_fr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 12.25h.01m3.99 0h.01M10 16h.01M14 16h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ysqkh55uc {
  width: 9.5px;
  height: 18.5px;
  x: 7.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.zz9p51bci {
  cx: 12px;
  cy: 7px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
