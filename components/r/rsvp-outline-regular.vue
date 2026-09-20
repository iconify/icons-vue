<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c8jtagpjt"/><path class="leo1-zbey"/><path class="l_u_8t5pe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rsvp-outline-regular" /></template>
<style>
.c8jtagpjt {
  d: path("M7 9v10h14V9Z");
}

.l_u_8t5pe {
  d: path("m6 11 -3 3 3 3");
}

.leo1-zbey {
  d: path("m7 9 7 7 7 -7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
