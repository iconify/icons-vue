<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="qwey1eb1c"/><path class="tb6q2fbtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:table-football-sharp" /></template>
<style>
.qwey1eb1c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 4.25h15.5v15.5H4.25zM2.75 12h18.5M8.5 9.5v5m7-5v5");
}

.tb6q2fbtf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
