<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ctt_dn_1e"/><path class="wae8aklke"/><path class="oib43sizw"/><path class="fezibpbwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:token-count-outline-regular" /></template>
<style>
.ctt_dn_1e {
  d: path("M2 11a3 3 0 0 1 3 -3 3 3 0 0 1 3 3 3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3");
}

.fezibpbwf {
  d: path("M3 18h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oib43sizw {
  d: path("M18 10a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
}

.wae8aklke {
  d: path("M10 11a3 3 0 0 1 3 -3 3 3 0 0 1 3 3 3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3");
}

</style>
