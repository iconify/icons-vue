<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gwjllcbqv"/><path class="vtt-aac3x"/><path class="u-njwih0q"/><path class="vgy66lb4b"/><path class="dc3nx_s6e"/><path class="iu97z3z3z"/><path class="ipkach1qn"/><path class="xslfg2evh"/><path class="axrnp4b4f"/><path class="fmr2g_bno"/><path class="yhgzmt2de"/><path class="yw_llwb7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:weather-station-duotone-bold" /></template>
<style>
.axrnp4b4f {
  d: path("M5 6h14");
}

.dc3nx_s6e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 6h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fmr2g_bno {
  d: path("M3 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.iu97z3z3z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12h6v4h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u-njwih0q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vgy66lb4b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 21h12");
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
