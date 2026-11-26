<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qwkwe-b6h"/><path class="ut17vmb_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stroke-line-join-round-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qwkwe-b6h {
  stroke-opacity: 0.4;
  d: path("M11 22L11 11L22 11");
}

.ut17vmb_f {
  d: path("M3 22L3 11C3 6.5817 6.5817 3 11 3L22 3");
}

</style>
