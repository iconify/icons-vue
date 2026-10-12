<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lwof3sbqm"/><path class="av9d3ab_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:service-animal-sharp" /></template>
<style>
.av9d3ab_y {
  d: path("M5.75 19.5h-3v1.75m11-8.75v3m-1.5-1.5h3");
}

.lwof3sbqm {
  d: path("M5.5 20.65V17.5l.32-.51l1.86-2.98l.32-.51l.45-.4l3.6-3.2l.45-.4l.12-.59l.51-2.57q.12-.59.37-1.14l.75-1.65l.25-.55l.46.38l.58.49l.46.38l.56.21l3.63 1.33l.56.21l-.07.6l-.11.8l-.07.6l-.59.1l-1.82.3l-.59.1l-.04.6l-.17 2.8q-.04.6-.02 1.2l.21 7.55l.02.6H15l-.04-.6l-.17-3.05l-.04-.6l-.45.4l-1.35 1.2l-.45.4v2.25h-7z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
