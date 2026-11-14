<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h0wlljbkg"/><path class="q5vjd7bqj"/><path class="x5qyo_byt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-taxi" /></template>
<style>
.h0wlljbkg {
  d: path("M2.5 16.5v-3.75l3-1l3-4.25h7l3 4.25l3 1v3.75Z");
}

.q5vjd7bqj {
  fill: currentColor;
  d: path("M10 4.5h4v3h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x5qyo_byt {
  d: path("M5.5 11.75h13M5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
