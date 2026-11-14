<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ieqm6w0dw"/><path class="cshjojgyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:speech-recognition" /></template>
<style>
.cshjojgyj {
  d: path("M6.25 10.5a5.75 5.75 0 0 0 11.5 0M12 16.25V21M4 6.5a6 6 0 0 0 0 7m16-7a6 6 0 0 1 0 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ieqm6w0dw {
  d: path("M12 2.5za3 3 0 0 1 3 3v5a3 3 0 0 1-3 3a3 3 0 0 1-3-3v-5a3 3 0 0 1 3-3");
}

</style>
