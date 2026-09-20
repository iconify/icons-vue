<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ymp2b4b6u"/><path class="xnynfexru"/><path class="pt-3kkb2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:origin-shield-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pt-3kkb2k {
  d: path("M9 11h6");
}

.xnynfexru {
  d: path("M8.5 11a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.ymp2b4b6u {
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
}

</style>
