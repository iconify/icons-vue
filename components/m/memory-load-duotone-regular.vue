<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vul_uwbfe"/><path class="wxx-lxpns"/><path class="ashjd6b6l"/><path class="qvr2dp0fw"/><path class="ysbzwbbjy"/><path class="nrqy16b7j"/><path class="qnmmmsbha"/><path class="ldkstzszf"/><path class="x58_p1b1n"/><path class="aigfccrzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-load-duotone-regular" /></template>
<style>
.aigfccrzm {
  d: path("M19.5 8.5 22 11l-2.5 2.5");
}

.ashjd6b6l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldkstzszf {
  d: path("M3 16h11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nrqy16b7j {
  d: path("M3 6h11");
}

.qnmmmsbha {
  d: path("M3 11h11");
}

.qvr2dp0fw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 11h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vul_uwbfe {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wxx-lxpns {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x58_p1b1n {
  d: path("M17 11h5");
}

.ysbzwbbjy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19.5 8.5 22 11l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
