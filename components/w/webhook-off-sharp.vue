<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fuziswjho"/><path class="z8dzjqawa"/><path class="izsik4bwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:webhook-off-sharp" /></template>
<style>
.fuziswjho {
  d: path("M17.4 16.48h-6.685l-.935 1.71A3.6 3.6 0 0 1 3 16.5l.016-.991l.494-.809");
}

.izsik4bwk {
  d: path("m12 6.6l2.82 5.16l.616 1.14H17.4a3.6 3.6 0 0 1 0 7.2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z8dzjqawa {
  d: path("m6.6 16.5l2.82-5.2l.626-1.135L8.97 8.51a3.6 3.6 0 1 1 6.2-3.66");
}

</style>
