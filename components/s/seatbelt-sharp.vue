<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="za-jh4x_l"/><path class="j_im5_bmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seatbelt-sharp" /></template>
<style>
.j_im5_bmk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.39 15.62h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.za-jh4x_l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.34 4.25l2.11 1.77l.57.48l.49-.57l.16-.19l.48-.58l.57.48l3.45 2.9l.58.48l-.49.57l-.8.96l-.32.38l.38.32l.96.81l.8-.96l.81-.96l1.72 1.45l1.91 1.61l1.73 1.44L20 16.37l-2.25 2.68l-1.44 1.72l-1.73-1.45l-1.91-1.6l-1.73-1.45l.81-.96l.8-.95l-.96-.81l-.38-.32l-.32.38l-.8.96l-.49.58l-.57-.49l-3.45-2.89l-.57-.48l.48-.57l.16-.2l.48-.57l-.57-.48L3.45 7.7l-.57-.48l.48-.58l1.93-2.3l.48-.57zm4.18 5.14l-1.29 1.53");
}

</style>
