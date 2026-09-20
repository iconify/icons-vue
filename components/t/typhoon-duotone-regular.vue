<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dktry7bqc"/><path class="ma55h4y1z"/><path class="ze0s3hbzk"/><path class="ifrpdr60i"/><path class="onpxwybhz"/><path class="bo51iypxr"/><path class="xz82qebme"/><path class="lz9b4vtgl"/><path class="glv5tabri"/><path class="x-fkne0xd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:typhoon-duotone-regular" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.glv5tabri {
  d: path("M19 12V5");
}

.ifrpdr60i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 12V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lz9b4vtgl {
  d: path("M5 12a7 7 0 0 1 14 0");
}

.ma55h4y1z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 12a7 7 0 0 1 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.onpxwybhz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x-fkne0xd {
  d: path("M5 12v7");
}

.xz82qebme {
  d: path("M19 12a7 7 0 0 1 -14 0");
}

.ze0s3hbzk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 12a7 7 0 0 1 14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
