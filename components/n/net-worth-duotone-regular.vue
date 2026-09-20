<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jzeve79sx"/><path class="chupkuwbv"/><path class="kj672_yfn"/><path class="c5wjx8n3c"/><path class="x4q3oe16k"/><path class="x5li7lwaz"/><path class="jwnes9bsk"/><path class="ymw3aibdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:net-worth-duotone-regular" /></template>
<style>
.c5wjx8n3c {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 19h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.chupkuwbv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 7h18M3 7a3 3 0 0 0 6 0m6 0a3 3 0 0 0 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jwnes9bsk {
  d: path("M8 19h8");
}

.jzeve79sx {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kj672_yfn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x4q3oe16k {
  d: path("M3 7h18M3 7a3 3 0 0 0 6 0m6 0a3 3 0 0 0 6 0");
}

.x5li7lwaz {
  d: path("M12 7v12");
}

.ymw3aibdo {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
