<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="gpkgke1tp"/><path class="mtyi5cckm"/><circle class="oic94lxlh"/><path class="c46x2570c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:safety-shower" /></template>
<style>
.c46x2570c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.75 11h.01M15 13.25h.01M17.25 11h.01");
}

.gpkgke1tp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21.25v-16A2.5 2.5 0 0 1 8 2.75h7V4M3 21.25h5");
}

.mtyi5cckm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 7.5a3.5 3.5 0 0 1 7 0Zm-2-4.75V10");
}

.oic94lxlh {
  cx: 9.5px;
  cy: 12.25px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
