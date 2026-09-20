<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gwjllcbqv"/><path class="vtt-aac3x"/><path class="t511ecujx"/><path class="ck_r08b8b"/><path class="o0arf079a"/><path class="xbgca8j8q"/><path class="ipkach1qn"/><path class="xslfg2evh"/><path class="axrnp4b4f"/><path class="fmr2g_bno"/><path class="yhgzmt2de"/><path class="yw_llwb7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:weather-station-duotone-thin" /></template>
<style>
.axrnp4b4f {
  d: path("M5 6h14");
}

.ck_r08b8b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 21h12");
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

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ipkach1qn {
  d: path("M12 6v15");
}

.o0arf079a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 6h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t511ecujx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vtt-aac3x {
  fill: currentColor;
  d: path("M17 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xbgca8j8q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12h6v4h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
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
