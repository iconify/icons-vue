<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tk1ko_brk"/><path class="o68ddy18u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:slider-horizontal-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o68ddy18u {
  d: path("M20 19C20 17.34 18.6569 16 17 16H15C13.3431 16 12 17.34 12 19M20 19C20 20.66 18.6569 22 17 22H15C13.3431 22 12 20.66 12 19M20 19H22M12 19H2M2 4V10C2 11.1 2.8954 12 4 12H20C21.1046 12 22 11.1 22 10V4C22 2.9 21.1046 2 20 2H4C2.8954 2 2 2.9 2 4Z");
}

.tk1ko_brk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 15C18.8639 15 20.43 16.27 20.874 18H22C22.5523 18 23 18.45 23 19C23 19.55 22.5523 20 22 20H20.874C20.43 21.73 18.8639 23 17 23H15C13.1361 23 11.57 21.73 11.126 20H2C1.4477 20 1 19.55 1 19C1 18.45 1.4477 18 2 18H11.126C11.57 16.27 13.1361 15 15 15H17ZM20 1C21.6569 1 23 2.34 23 4V10C23 11.66 21.6569 13 20 13H4C2.3432 13 1 11.66 1 10V4C1 2.34 2.3431 1 4 1H20Z");
  stroke: none;
}

</style>
