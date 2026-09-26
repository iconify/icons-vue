<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ahwfs1brb"/><path class="f97cc674d"/><path class="xgdz-8_qq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:music-note-off-two-tone" /></template>
<style>
.ahwfs1brb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 18C10 20.2091 8.2091 22 6 22C3.7909 22 2 20.2091 2 18C2 15.7909 3.7909 14 6 14C8.2091 14 10 15.7909 10 18Z");
  stroke: none;
}

.f97cc674d {
  stroke-opacity: 0.4;
  d: path("M18.7518 13.095C19.8046 13.3666 20.6334 14.1954 20.905 15.2482M10.4202 4.7633L21 3V15.3431");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xgdz-8_qq {
  d: path("M9 18C9 19.6569 7.6569 21 6 21C4.3431 21 3 19.6569 3 18C3 16.3431 4.3431 15 6 15C7.6569 15 9 16.3431 9 18ZM9 18V9M18.8715 18.8715C18.5957 18.9551 18.3031 19 18 19C16.3431 19 15 17.6569 15 16C15 15.6969 15.0449 15.4043 15.1285 15.1285M2 2L22 22");
}

</style>
