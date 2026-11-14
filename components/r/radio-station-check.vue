<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rj0hswbxy"/><path class="ghyflyb-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:radio-station-check" /></template>
<style>
.ghyflyb-z {
  d: path("M8 10a4 4 0 0 1 8 0m-9.5 0h3v3.5h-3Zm8 0h3v3.5h-3Zm.25 8l2 2L21 15.75");
}

.rj0hswbxy {
  d: path("M10.8 18H2.5V3h19v9.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
