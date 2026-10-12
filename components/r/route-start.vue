<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="zvb-krb3m"/><path class="qvoc8gbpg"/><path class="hq29vkblf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:route-start" /></template>
<style>
.hq29vkblf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 17.5h2c2.25 0 3.5-1.25 3.5-3.5V9c0-2.25 1.25-3.5 3.5-3.5h2");
}

.qvoc8gbpg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 17.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zvb-krb3m {
  cx: 6.5px;
  cy: 17.5px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
