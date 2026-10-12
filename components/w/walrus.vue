<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="hptsy9b7x"/><path class="pnyzhrb6l"/><path class="hmk2_gkmt"/><path class="dxzhv-zcp"/><path class="kz30hnxkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:walrus" /></template>
<style>
.dxzhv-zcp {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 12.5h.01m4.49 0h.01");
}

.hmk2_gkmt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11c.6-.6 1.4-1 2.25-1a2.5 2.5 0 0 1 0 5c-.85 0-1.65-.4-2.25-1c-.6.6-1.4 1-2.25 1a2.5 2.5 0 0 1 0-5c.85 0 1.65.4 2.25 1");
}

.hptsy9b7x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 13.5c-1.25 1.25-1.75 3.25-1.75 5.25c0 1.25.75 2 2 2h12.5c1.25 0 2-.75 2-2c0-2-.5-4-1.75-5.25M12 5c4.25 0 7.25 2.25 7.25 5.25v.5c0 1.25-1 2.25-2.25 2.25H7c-1.25 0-2.25-1-2.25-2.25v-.5c0-3 3-5.25 7.25-5.25");
}

.kz30hnxkh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 15v4m4.5-4v4");
}

.pnyzhrb6l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 7.5h.01m4.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
