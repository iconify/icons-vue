<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="a4lcn3oby"/><path class="uau9y_dpp"/><path class="afk3glbhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stream-to-display-sharp" /></template>
<style>
.a4lcn3oby {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v12.5H2.75zM12 16.25v4m-3.5 0h7");
}

.afk3glbhf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.75h.01");
}

.uau9y_dpp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.88 10.63L12 8.513l2.12 2.117M7.76 8.51a6 6 0 0 1 8.48 0");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
