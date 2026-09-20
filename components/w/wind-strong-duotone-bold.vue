<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wek-7zrox"/><path class="sqbfpsk4m"/><path class="v2tw47b3s"/><path class="ugds1obry"/><path class="br1blbchr"/><path class="t72hs-46k"/><path class="apq8ywbbc"/><path class="e0v4wgb4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wind-strong-duotone-bold" /></template>
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

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sqbfpsk4m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t72hs-46k {
  d: path("M3 11h17");
}

.ugds1obry {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h12a3 3 0 1 1 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v2tw47b3s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wek-7zrox {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h12a3 3 0 1 0 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
