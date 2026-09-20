<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mg7aqnbsf"/><path class="j835zw5-z"/><path class="i80sg_6wn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:underline-wavy-outline-regular" /></template>
<style>
.i80sg_6wn {
  d: path("m3 16 2.5 -2.5L8 16l2.5 -2.5L13 16l2.5 -2.5L18 16l2.5 -2.5");
}

.j835zw5-z {
  d: path("M3 9h18");
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
