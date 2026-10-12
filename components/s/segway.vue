<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="ecj-ocb5d"/><path class="pzhmyob9w"/><path class="tso-140cr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:segway" /></template>
<style>
.ecj-ocb5d {
  cx: 12px;
  cy: 18px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pzhmyob9w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18h.01");
}

.tso-140cr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 14.75h14m-7 0L14.5 4m-2.25 0h4.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
