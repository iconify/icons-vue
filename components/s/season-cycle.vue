<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rn6sbubux"/><path class="bsyu8jmin"/><path class="v_v2lg0mh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:season-cycle" /></template>
<style>
.bsyu8jmin {
  d: path("M3 17.25L4 15l2.25 1M4.013 9.093a8.5 8.5 0 0 1 15.974 0");
}

.rn6sbubux {
  d: path("M19.987 14.907a8.5 8.5 0 0 1-15.974 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v_v2lg0mh {
  d: path("M21 6.75L20 9l-2.25-1M9 15c0-4.5 2.5-6 6-6q0 6-6 6Zm1.25-1.25l2.5-2.5");
}

</style>
