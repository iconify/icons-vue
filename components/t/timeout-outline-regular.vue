<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sl0tqnboi"/><path class="yf0ac-1wm"/><path class="nc5ku3b2p"/><path class="jfgb4ctmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:timeout-outline-regular" /></template>
<style>
.jfgb4ctmg {
  d: path("m21 8 -4 4");
}

.nc5ku3b2p {
  d: path("m17 8 4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sl0tqnboi {
  d: path("M4 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.yf0ac-1wm {
  d: path("M10 9v3h3");
}

</style>
