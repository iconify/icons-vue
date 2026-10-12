<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yz_8bm0vu"/><path class="wgvo3iwrh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:squid-sharp" /></template>
<style>
.wgvo3iwrh {
  d: path("m10.11 5.69l-4.4 1.87l-.46.19l.49.1l2.77.55l.49.1l.23-.44l1.11-2.12l.23-.44zm3.78 0l4.4 1.87l.46.19l-.49.1l-2.77.55l-.49.1l-.23-.44l-1.11-2.12l-.23-.44zM9.6 15.75V19l-1.5 2m3.9-5.25v5.5m2.4-5.5V19l1.5 2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yz_8bm0vu {
  d: path("m12.42 3.55l2.16 4.15l.42.8l-.08.9l-.34 3.7l-.08.9h-5l-.08-.9l-.34-3.7L9 8.5l.42-.8l2.16-4.15l.42-.8z");
}

</style>
