<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fb6xkzb1k"/><path class="xy1wgr6wy"/><path class="g_k4bub3x"/><path class="guw4_4ovg"/><path class="so--shb1m"/><path class="judl2rxer"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trust-fund-duotone-regular" /></template>
<style>
.fb6xkzb1k {
  fill: currentColor;
  d: path("M6 9h12v10a3 3 0 0 1 -3 3H9a3 3 0 0 1 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.g_k4bub3x {
  d: path("M6 9h12v10a3 3 0 0 1 -3 3H9a3 3 0 0 1 -3 -3Z");
}

.guw4_4ovg {
  d: path("M8 9V4h8v5");
}

.judl2rxer {
  d: path("M10.5 15.5a1.5 1.5 0 0 1 3 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.so--shb1m {
  d: path("M9 15.5h6v3H9Z");
}

.xy1wgr6wy {
  fill: currentColor;
  d: path("M9 15.5h6v3H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
