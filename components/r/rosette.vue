<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k71qq8bfi"/><path class="t7mcsvn8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rosette" /></template>
<style>
.k71qq8bfi {
  d: path("m12 2.5l1.488 1.446l2.012-.508l.566 1.996L18.062 6l-.508 2.012L19 9.5l-1.446 1.488l.508 2.012l-1.996.566l-.566 1.996l-2.012-.508L12 16.5l-1.488-1.446l-2.012.508l-.566-1.996L5.938 13l.508-2.012L5 9.5l1.446-1.488L5.938 6l1.996-.566l.566-1.996l2.012.508Z");
}

.t7mcsvn8e {
  d: path("M8.75 14.75L7.5 21.5l4.5-2.25l4.5 2.25l-1.25-6.75M12 9.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
