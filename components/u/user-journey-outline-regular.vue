<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yhbbndf5c"/><path class="fd4ngbb9a"/><path class="zohykibek"/><path class="j49v8ng1j"/><path class="fop9i_hvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:user-journey-outline-regular" /></template>
<style>
.fd4ngbb9a {
  d: path("m6 17 4 -4");
}

.fop9i_hvr {
  d: path("M19 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.j49v8ng1j {
  d: path("m14 9 4 -4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yhbbndf5c {
  d: path("M2 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zohykibek {
  d: path("M10 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
