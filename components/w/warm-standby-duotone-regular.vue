<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="be83lpb1j"/><path class="nrlkc9bnf"/><path class="rbe8j9b-u"/><path class="dvoob7u7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:warm-standby-duotone-regular" /></template>
<style>
.be83lpb1j {
  fill: currentColor;
  d: path("M4 12a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.dvoob7u7j {
  d: path("M13.5 9.5v5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nrlkc9bnf {
  d: path("M4 12a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

.rbe8j9b-u {
  d: path("M10.5 9.5v5");
}

</style>
