<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c54duacdo"/><path class="es4r-tbix"/><path class="iogxcvc1e"/><path class="xiot9nbkk"/><path class="cg-i-7_rc"/><path class="nrqy16b7j"/><path class="qnmmmsbha"/><path class="ldkstzszf"/><path class="x58_p1b1n"/><path class="aigfccrzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-load-duotone-bold" /></template>
<style>
.aigfccrzm {
  d: path("M19.5 8.5 22 11l-2.5 2.5");
}

.c54duacdo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cg-i-7_rc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19.5 8.5 22 11l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.es4r-tbix {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iogxcvc1e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldkstzszf {
  d: path("M3 16h11");
}

.nrqy16b7j {
  d: path("M3 6h11");
}

.qnmmmsbha {
  d: path("M3 11h11");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x58_p1b1n {
  d: path("M17 11h5");
}

.xiot9nbkk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 11h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
