<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c3pyddbgv"/><path class="ipz7hbbkr"/><path class="bcggdz8nd"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rainbow-gold" /></template>
<style>
.bcggdz8nd {
  d: path("M10 12.25a3 3 0 0 1 6 0m-12.5 3h8l-1 5.25h-6ZM14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.c3pyddbgv {
  d: path("M4.5 12.25a8.5 8.5 0 0 1 17 0");
}

.ipz7hbbkr {
  d: path("M7.25 12.25a5.75 5.75 0 0 1 11.5 0");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
