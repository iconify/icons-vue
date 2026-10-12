<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="rm-79pv8l"/><path class="i780oo3eq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:protest-sign-sharp" /></template>
<style>
.i780oo3eq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11.75h.01");
}

.rm-79pv8l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.54 4.3l11.93-1.25l1.99-.21l.21 1.99l.57 5.47l.21 1.99l-1.99.21l-11.93 1.25l-1.99.21l-.21-1.99l-.57-5.47l-.21-1.99zM12 13.25v8m0-15.5v3.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
