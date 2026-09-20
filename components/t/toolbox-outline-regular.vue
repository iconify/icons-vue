<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oy6b_1b_a"/><path class="ltriwmbuu"/><path class="yngda3bvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:toolbox-outline-regular" /></template>
<style>
.ltriwmbuu {
  d: path("M8 10a4 4 0 0 1 8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oy6b_1b_a {
  d: path("M3 20V10h18v10Z");
}

.yngda3bvc {
  d: path("M3 15h18");
}

</style>
