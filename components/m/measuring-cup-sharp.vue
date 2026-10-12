<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ow5uh3bpn"/><path class="dx0-kz08m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:measuring-cup-sharp" /></template>
<style>
.dx0-kz08m {
  d: path("M15.95 8.5h4.3v7h-4.7m-5.3-6.25h3.25m-2 3.25h2m-3.25 3.25h3.25");
}

.ow5uh3bpn {
  d: path("M5 4.75h11.25L16.17 6l-.84 13.75l-.08 1.25H6l-.17-1.24L3.92 5.99l-.17-1.24z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
