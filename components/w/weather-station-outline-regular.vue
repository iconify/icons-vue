<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ipkach1qn"/><path class="xslfg2evh"/><path class="axrnp4b4f"/><path class="fmr2g_bno"/><path class="yhgzmt2de"/><path class="yw_llwb7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:weather-station-outline-regular" /></template>
<style>
.axrnp4b4f {
  d: path("M5 6h14");
}

.fmr2g_bno {
  d: path("M3 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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
