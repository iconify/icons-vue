<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yerw84_9m"/><path class="t69363l7x"/><path class="v5slp2tuk"/><path class="vw-y0febs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reusable-bag-duotone-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t69363l7x {
  d: path("M6 8v13h12V8Z");
}

.v5slp2tuk {
  d: path("M6 8a3 3 0 0 1 6 0");
}

.vw-y0febs {
  d: path("M12 8a3 3 0 0 1 6 0");
}

.yerw84_9m {
  fill: currentColor;
  d: path("M6 8v13h12V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
