<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="eodvx3bcu"/><path class="fky8vgb_s"/><path class="d-ycm7dex"/><path class="tw1khnbtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quantize-4bit-duotone-bold" /></template>
<style>
.d-ycm7dex {
  d: path("m3 9 6 -6");
}

.eodvx3bcu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 9 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fky8vgb_s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 21h5v-5h5v-5h5V6h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tw1khnbtv {
  d: path("M3 21h5v-5h5v-5h5V6h3");
}

</style>
