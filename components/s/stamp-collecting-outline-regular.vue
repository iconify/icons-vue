<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ak36m6b8g"/><path class="f4nuxtbsp"/><path class="o9j8_ob8u"/><path class="ozywi-m1p"/><path class="elm0fn4gd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stamp-collecting-outline-regular" /></template>
<style>
.ak36m6b8g {
  d: path("M4 5h16v14H4Zm0 0");
}

.elm0fn4gd {
  d: path("M19 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.f4nuxtbsp {
  d: path("M8 9h8v6H8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o9j8_ob8u {
  d: path("M3 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ozywi-m1p {
  d: path("M3 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
