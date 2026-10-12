<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="oigc5ltrf"/><path class="wvswjpbce"/><path class="ej4_3wbll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:place-of-worship" /></template>
<style>
.ej4_3wbll {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h.01");
}

.oigc5ltrf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 20.5v-8.75q0-.75.58-1.22l4.34-3.56q.58-.47 1.16 0l4.34 3.56q.58.47.58 1.22v8.75q0 .75-.75.75h-9.5q-.75 0-.75-.75");
}

.wvswjpbce {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 21.25v-2.5a1.5 1.5 0 0 1 3 0v2.5m-1.5-9.5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 1 1 0-2.5m-9.25 9.5h18.5M12 6.5V4");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
