<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vw-vqmbue"/><path class="tx_ze2sua"/><path class="festcnvxk"/><path class="bx3fv3b8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:optimiser-duotone-bold" /></template>
<style>
.bx3fv3b8c {
  d: path("M12 13v4");
}

.festcnvxk {
  d: path("m3 7 6 6h6l6 -6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tx_ze2sua {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 13v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vw-vqmbue {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 7 6 6h6l6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
