<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l7ij41ifm"/><path class="vlp5q5bxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:moon-star-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l7ij41ifm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 12c0 5.523-4.477 10-10 10S2 17.523 2 12S6.477 2 12 2a1 1 0 0 1 .625 1.781a5.4 5.4 0 0 0 0 8.438a5.403 5.403 0 0 0 7.594-.844A1.002 1.002 0 0 1 22 12");
}

.vlp5q5bxg {
  d: path("m13.986 6l.003-.001c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375L16 3.986a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177l.003.001a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375l-.001.003a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L13.986 8a1 1 0 0 1 0-2");
}

</style>
