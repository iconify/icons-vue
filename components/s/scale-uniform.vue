<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s4hcrab3l"/><path class="o19gn58cb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scale-uniform" /></template>
<style>
.o19gn58cb {
  d: path("M8 9.75L12 12l4-2.25M12 12v4.5m-9-10V3h3.5M3 3l2.75 2.75M17.5 3H21v3.5M21 3l-2.75 2.75M3 17.5V21h3.5M3 21l2.75-2.75M21 17.5V21h-3.5m3.5 0l-2.75-2.75");
}

.s4hcrab3l {
  d: path("m12 7.5l4 2.25v4.5l-4 2.25l-4-2.25v-4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
