<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="dv9c_lbbq"/><path class="sci58wslm"/><path class="bgq0jqblk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pinwheel-toy-sharp" /></template>
<style>
.bgq0jqblk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 15.25v6");
}

.dv9c_lbbq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.39 7.18l.85-3.37l.15-.58l.27.53l1.46 2.89l.27.53l-.59.11l-1.97.36l-.59.11zm.43 3.21l3.37.85l.58.15l-.53.27l-2.89 1.46l-.53.27l-.11-.59l-.36-1.97l-.11-.59zm-3.21.43l-.85 3.37l-.15.58l-.27-.53l-1.46-2.89l-.27-.53l.59-.11l1.97-.36l.59-.11zm-.43-3.21l-3.37-.85l-.58-.15l.53-.27l2.89-1.46l.53-.27l.11.59l.36 1.97l.11.59z");
}

.sci58wslm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
