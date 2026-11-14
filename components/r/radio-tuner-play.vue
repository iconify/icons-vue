<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sgywqpigz"/><path class="c48-t23mb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:radio-tuner-play" /></template>
<style>
.c48-t23mb {
  d: path("M5.25 10.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm3.25 0V7.25m6.25 2.5h4m-2-3.25v5.25m-2 2.25l6.75 4l-6.75 4Z");
}

.sgywqpigz {
  d: path("M11.9 17.5H2.5v-14h19v11.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
