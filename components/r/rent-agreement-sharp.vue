<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mqkg9kykg"/><path class="kzvghobak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rent-agreement-sharp" /></template>
<style>
.kzvghobak {
  d: path("M9 10.25v-3L12 5l3 2.25v3Zm-1 3.5h8m-8 4l1.313-2.187l.437 2.187l.363 1.813L11.5 17.25l.911-1.518L13 17.5h3");
}

.mqkg9kykg {
  d: path("M4.25 2.75h15.5v18.5H4.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
