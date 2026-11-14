<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b7_n66beh"/><path class="rxtayfdmd"/><path class="g0iyfmbel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:price-sticker-roll" /></template>
<style>
.b7_n66beh {
  d: path("M2.5 7.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

.g0iyfmbel {
  d: path("M9.75 15.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm4 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm4 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.rxtayfdmd {
  d: path("M7 12h14.5v6.5h-13M7 7.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
