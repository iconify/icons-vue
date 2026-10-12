<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="z8sa82bum"/><path class="uro4albms"/><rect class="py-oz0shh"/><circle class="dwvbaw88m"/><circle class="iblfxcc2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trojan-horse" /></template>
<style>
.dwvbaw88m {
  cx: 7.5px;
  cy: 19.75px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iblfxcc2h {
  cx: 16.5px;
  cy: 19.75px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.py-oz0shh {
  width: 15px;
  height: 2.75px;
  x: 4.5px;
  y: 15.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.uro4albms {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.75 6.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z8sa82bum {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 15.5V10c0-3.6 2.4-6.4 5.75-7L14 4.5l3.6 3.4c.55.55.65 1.4.2 2l-.55.75c-.45.6-1.3.75-1.9.3L13.5 9.5v6Z");
}

</style>
