<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b-fhdniix"/><path class="eoa7zubuy"/><path class="kut6h2oks"/><path class="mtc590bck"/><path class="ceatt7y_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:secret-leak-outline-regular" /></template>
<style>
.b-fhdniix {
  d: path("M2 9a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.ceatt7y_b {
  d: path("M18 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.eoa7zubuy {
  d: path("M5 7a3 3 0 0 1 6 0");
}

.kut6h2oks {
  d: path("M18 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mtc590bck {
  d: path("M16 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
