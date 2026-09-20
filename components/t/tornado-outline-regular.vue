<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mg7aqnbsf"/><path class="mlhk78k2d"/><path class="l0v-b4kbr"/><path class="wy2n5sbyh"/><path class="b__1sjw6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tornado-outline-regular" /></template>
<style>
.b__1sjw6v {
  d: path("m11 18 2 2");
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.mlhk78k2d {
  d: path("M5 8h14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wy2n5sbyh {
  d: path("M10 16h4");
}

</style>
