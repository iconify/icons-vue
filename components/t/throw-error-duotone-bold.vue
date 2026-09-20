<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kta-v8eyv"/><path class="efgcqsb-z"/><path class="pxmcfjbnu"/><path class="bh4gsivfq"/><path class="u552kxblg"/><path class="pdpzifbii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:throw-error-duotone-bold" /></template>
<style>
.bh4gsivfq {
  d: path("m13 9 2.5 -2.5");
}

.efgcqsb-z {
  fill: currentColor;
  d: path("M17.5 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kta-v8eyv {
  fill: currentColor;
  d: path("M3 11a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pdpzifbii {
  d: path("M17.5 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.pxmcfjbnu {
  d: path("M3 11a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u552kxblg {
  d: path("M18.5 2.5V5");
}

</style>
