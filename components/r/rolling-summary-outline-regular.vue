<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d8z1r1beo"/><path class="wzx0dxb2r"/><path class="jlfjgzbqx"/><path class="x1_r36phd"/><path class="ae0h5kb0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rolling-summary-outline-regular" /></template>
<style>
.ae0h5kb0o {
  d: path("M9 15h6");
}

.d8z1r1beo {
  d: path("M15 5h3a3 3 0 0 1 3 3v9a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

.jlfjgzbqx {
  d: path("M9 9h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wzx0dxb2r {
  d: path("m12 2 3 3 -3 3");
}

.x1_r36phd {
  d: path("M9 12h6");
}

</style>
