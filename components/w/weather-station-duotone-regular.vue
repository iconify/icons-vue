<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gwjllcbqv"/><path class="vtt-aac3x"/><path class="q7n2lr1pp"/><path class="ezik40n3m"/><path class="p5p2h3eqo"/><path class="g1nx_ou-i"/><path class="ipkach1qn"/><path class="xslfg2evh"/><path class="axrnp4b4f"/><path class="fmr2g_bno"/><path class="yhgzmt2de"/><path class="yw_llwb7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:weather-station-duotone-regular" /></template>
<style>
.axrnp4b4f {
  d: path("M5 6h14");
}

.ezik40n3m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 21h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fmr2g_bno {
  d: path("M3 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.g1nx_ou-i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 12h6v4h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gwjllcbqv {
  fill: currentColor;
  d: path("M3 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ipkach1qn {
  d: path("M12 6v15");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p5p2h3eqo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 6h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q7n2lr1pp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 6v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vtt-aac3x {
  fill: currentColor;
  d: path("M17 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xslfg2evh {
  d: path("M6 21h12");
}

.yhgzmt2de {
  d: path("M17 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.yw_llwb7j {
  d: path("M12 12h6v4h-6");
}

</style>
