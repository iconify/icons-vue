<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i45girxkv"/><path class="heagg9bky"/><path class="kl6l2s17r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:welcome-email" /></template>
<style>
.heagg9bky {
  d: path("m2.5 11l9.5 6l9.5-6");
}

.i45girxkv {
  d: path("M2.5 11v8.5A1.5 1.5 0 0 0 4 21h16a1.5 1.5 0 0 0 1.5-1.5V11");
}

.kl6l2s17r {
  d: path("M8.25 3.5V8c0 2.5 1.75 4 4 4s4.25-1.5 4.25-4V3.5m-5.5-1V7m2.75-4.5V7m-5.5 1.5L5.5 5.75M19.25 4L21 2.75m-1.5 4.5h2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
