<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u5kuez3us"/><path class="c5cmy2bxq"/><path class="y814rsb-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:system-prompt-outline-regular" /></template>
<style>
.c5cmy2bxq {
  d: path("M9 10h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u5kuez3us {
  d: path("M15.5 6H18a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3v-4l5 -5h2.5");
}

.y814rsb-q {
  d: path("M9 14h5");
}

</style>
