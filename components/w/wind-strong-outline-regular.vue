<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="br1blbchr"/><path class="t72hs-46k"/><path class="apq8ywbbc"/><path class="e0v4wgb4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wind-strong-outline-regular" /></template>
<style>
.apq8ywbbc {
  d: path("M3 15h14");
}

.br1blbchr {
  d: path("M3 6h12a3 3 0 1 0 -3 -3");
}

.e0v4wgb4v {
  d: path("M3 20h12a3 3 0 1 1 -3 -3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t72hs-46k {
  d: path("M3 11h17");
}

</style>
