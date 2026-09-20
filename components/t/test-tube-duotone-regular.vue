<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hy9ufxe6u"/><path class="y956i_bsc"/><path class="xbjl58b2q"/><path class="wk0v94gpu"/><path class="no2cffbmc"/><path class="sdu6a9xcp"/><path class="va9i39bae"/><path class="y07a50u1t"/><path class="pbz4y6llk"/><path class="c3wl0l-ou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:test-tube-duotone-regular" /></template>
<style>
.c3wl0l-ou {
  d: path("M19 13v6");
}

.hy9ufxe6u {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 3v12l3 3 3 -3V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.no2cffbmc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pbz4y6llk {
  d: path("M5 13v6");
}

.sdu6a9xcp {
  d: path("M9 3v12l3 3 3 -3V3");
}

.va9i39bae {
  d: path("M7 3h10");
}

.wk0v94gpu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xbjl58b2q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 13h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y07a50u1t {
  d: path("M5 13h14");
}

.y956i_bsc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
