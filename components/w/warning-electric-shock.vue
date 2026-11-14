<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ss7_y6i_h"/><path class="c87kbw-qo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:warning-electric-shock" /></template>
<style>
.c87kbw-qo {
  d: path("m12.75 9.75l-2.75 4h4l-2.75 3.75");
}

.ss7_y6i_h {
  d: path("m12 3l9.5 17.25h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
