<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="i3ge_w21d"/><path class="pnopb7b7a"/><path class="bdflu961o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:watermelon" /></template>
<style>
.bdflu961o {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10h.01M12 12.25h.01M15 10h.01");
}

.i3ge_w21d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.75h18.5a9.25 9.25 0 0 1-18.5 0");
}

.pnopb7b7a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7.75a6.5 6.5 0 0 0 13 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
