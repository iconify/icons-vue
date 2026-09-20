<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o0u5m7z1w"/><path class="qn86ywycs"/><path class="vx3m4bmzg"/><path class="zi3zfrtwz"/><path class="g_eatebwd"/><path class="prj9u5frn"/><path class="neof5acyb"/><path class="jg5yyubai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:swimming-race-duotone-regular" /></template>
<style>
.g_eatebwd {
  d: path("M5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.jg5yyubai {
  d: path("M3 16c3 -2 6 2 9 0s6 2 9 0");
}

.neof5acyb {
  d: path("m14 10 4 -4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o0u5m7z1w {
  fill: currentColor;
  d: path("M5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.prj9u5frn {
  d: path("M9 10h5");
}

.qn86ywycs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 10h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vx3m4bmzg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14 10 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zi3zfrtwz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16c3 -2 6 2 9 0s6 2 9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
