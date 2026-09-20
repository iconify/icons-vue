<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k-gv_lb9q"/><path class="cmh_klbjb"/><path class="g9c4ykb9u"/><path class="h1h08f6go"/><path class="w69b-gima"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:signature-crypto-outline-regular" /></template>
<style>
.cmh_klbjb {
  d: path("m5 10 4 4");
}

.g9c4ykb9u {
  d: path("M11 12h10");
}

.h1h08f6go {
  d: path("M15 12v3");
}

.k-gv_lb9q {
  d: path("M3 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w69b-gima {
  d: path("M19 12v4");
}

</style>
