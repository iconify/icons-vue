<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="vvlch2bde"/><rect class="jpl77-4ri"/><path class="t3ln9qbwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:market-stall" /></template>
<style>
.jpl77-4ri {
  width: 18.5px;
  height: 2.75px;
  x: 2.75px;
  y: 15px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.t3ln9qbwv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 12h.01M12 12h.01m3.49 0h.01");
}

.vvlch2bde {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.84 3.29l7.57 4.92q.84.54-.16.54H3.75q-1 0-.16-.54l7.57-4.92q.84-.54 1.68 0M4.75 8.75V15m14.5-6.25V15m-14.5 2.75v3.5m14.5-3.5v3.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
