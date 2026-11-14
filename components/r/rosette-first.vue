<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="judaibckp"/><path class="s2908hvms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rosette-first" /></template>
<style>
.judaibckp {
  d: path("m19 9l-1.75-2.25L17 4l-2.75-.25L12 2L9.75 3.75L7 4l-.25 2.75L5 9l1.75 2.25L7 14l2.75.25L12 16l2.25-1.75L17 14l.25-2.75Z");
}

.s2908hvms {
  d: path("M9.25 14.25L7 21l1.75-1l1.75 1.5L12 16l1.5 5.5l1.75-1.5L17 21l-2.25-6.75M9 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
