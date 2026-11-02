<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ktr2p3bbo"/><path class="le3yezbmj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:play-pause-duocolor-round" /></template>
<style>
.ktr2p3bbo {
  stroke-opacity: 0.4;
  d: path("M17 6v12m4-12v12");
}

.le3yezbmj {
  d: path("m6.11 6.336l6 4a2 2 0 0 1 0 3.328l-6 4C4.78 18.55 3 17.597 3 16V8c0-1.597 1.78-2.55 3.11-1.664");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
