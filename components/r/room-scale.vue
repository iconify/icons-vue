<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh3omg2mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:room-scale" /></template>
<style>
.jh3omg2mn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5.5h-3l-1 3.25m9-3.25h3l1 3.25m-15 6l-1 3.75h4m14-3.75l1 3.75h-4m-6.984-9h2.968a1.5 1.5 0 0 1 1.393.943l.8 2a1.5 1.5 0 0 1-1.393 2.057H9.716a1.5 1.5 0 0 1-1.393-2.057l.8-2a1.5 1.5 0 0 1 1.393-.943");
}

</style>
