<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qadduvbcb"/><path class="vpmg4cctx"/><path class="yvf3_7ucp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rosin" /></template>
<style>
.qadduvbcb {
  d: path("m2.5 17.5l15-15l3 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vpmg4cctx {
  d: path("m4.5 15.5l2-2l3 3l-2 2Zm5 1l11-11M18 14.75l3.25 1.75v3.75L18 22l-3.25-1.75V16.5Z");
}

.yvf3_7ucp {
  d: path("M14.75 16.5L18 18.25l3.25-1.75M18 18.25V22");
}

</style>
