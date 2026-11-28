<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="td12q8bzv"/><path class="kx6626any"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:train-front-tunnel" /></template>
<style>
.kx6626any {
  fill: currentColor;
  d: path("M11 15C11 15.5523 10.5523 16 10 16C9.4477 16 9 15.5523 9 15C9 14.4477 9.4477 14 10 14C10.5523 14 11 14.4477 11 15ZM15 15C15 15.5523 14.5523 16 14 16C13.4477 16 13 15.5523 13 15C13 14.4477 13.4477 14 14 14C14.5523 14 15 14.4477 15 15Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.td12q8bzv {
  d: path("M2 22L2 7C2 4.2386 4.2386 2 7 2L17 2C19.7614 2 22 4.2386 22 7L22 22M8 7L16 7C17.1046 7 18 7.8954 18 9L18 17C18 18.1046 17.1046 19 16 19L8 19C6.8954 19 6 18.1046 6 17L6 9C6 7.8954 6.8954 7 8 7ZM6 11L18 11M8 19L6.5 22M16 19L17.5 22");
}

</style>
