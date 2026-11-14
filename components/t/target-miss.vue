<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rs1wsibwn"/><path class="gc4q_0nxy"/><path class="kf11fzbfv"/><path class="k68fmw0ye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:target-miss" /></template>
<style>
.gc4q_0nxy {
  d: path("M5.75 14.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

.k68fmw0ye {
  d: path("m21 3l-3 8m-1.75-1.75l1.5 2.5l2-2M19.5 2.5L21 3l.75 1.5");
}

.kf11fzbfv {
  fill: currentColor;
  d: path("M8.5 14.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.rs1wsibwn {
  d: path("M2.5 14.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
