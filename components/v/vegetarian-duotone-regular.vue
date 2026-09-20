<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jmpakbqgq"/><path class="by2xacctu"/><path class="pgsklob1p"/><path class="sjot3p-qh"/><path class="sx4d4gbbz"/><path class="rhu0tub0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vegetarian-duotone-regular" /></template>
<style>
.by2xacctu {
  d: path("M6 3v5");
}

.jmpakbqgq {
  fill: currentColor;
  d: path("M14 18c0 -5 3 -8 8 -8 0 5 -3 8 -8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pgsklob1p {
  d: path("M10 3v5");
}

.rhu0tub0r {
  d: path("M14 18c0 -5 3 -8 8 -8 0 5 -3 8 -8 8");
}

.sjot3p-qh {
  d: path("M6 8h4");
}

.sx4d4gbbz {
  d: path("M8 8v13");
}

</style>
