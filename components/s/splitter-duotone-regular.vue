<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="asd1gsbjs"/><path class="rn124nbga"/><path class="wh01pcbbr"/><path class="jcxg2bbvb"/><path class="fyyr_6-1m"/><path class="ue-dwjbmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:splitter-duotone-regular" /></template>
<style>
.asd1gsbjs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fyyr_6-1m {
  d: path("m10 12 4 -4h7");
}

.jcxg2bbvb {
  d: path("M2 12h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rn124nbga {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 12 4 -4h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ue-dwjbmw {
  d: path("m10 12 4 4h7");
}

.wh01pcbbr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 12 4 4h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
