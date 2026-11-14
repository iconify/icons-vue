<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x797gdc8w"/><path class="t8lf677ok"/><path class="exogbkivh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:miss-shot" /></template>
<style>
.exogbkivh {
  d: path("M14 3.5q3.5 3.5 0 7");
}

.t8lf677ok {
  d: path("m3 13.5l2 7L7.5 17l2.5 3.5l2-7m.5-6.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm0 0h9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x797gdc8w {
  d: path("M2.5 13a5 1.5 0 1 0 10 0a5 1.5 0 1 0-10 0Z");
}

</style>
