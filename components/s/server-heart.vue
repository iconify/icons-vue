<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f9ui0hbju"/><path class="blis0jb9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:server-heart" /></template>
<style>
.blis0jb9s {
  d: path("M18.5 21.75L16 19a1.75 1.75 0 0 1 2.5-2.25A1.75 1.75 0 0 1 21 19Z");
}

.f9ui0hbju {
  d: path("M14.1 21H3V2.5h15.5v11.2M3 8.25h15.5M3 13.75h13.5m-10-8.5h.01M6.5 11h.01m-.01 6.25h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
