<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kpkshsyom"/><path class="d-wz3pjpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-windmill" /></template>
<style>
.d-wz3pjpu {
  d: path("M10.5 21.5v-3a1.5 1.5 0 0 1 3 0v3");
}

.kpkshsyom {
  d: path("M7 21.5L9 11h6l2 10.5Zm-.5-19l11 11m0-11l-11 11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
