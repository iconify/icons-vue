<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="snkxm00hi"/><path class="xgtwz7bri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:side-mirror-sharp" /></template>
<style>
.snkxm00hi {
  d: path("m5.24 5.74l7.02-.73l2.49-.26l.75 2.13l.75 2.12l-.19 2.49l-.12 1.52l-.19 2.49l-2.5.11l-6.5.28l-2.5.11l-.37-2.47l-.76-5.06L2.75 6z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xgtwz7bri {
  d: path("m6.74 8.13l5.02-.51L13 7.5l.06 1.25l.13 3l.06 1.25l-1.25.09l-4.5.32l-1.25.09l-.18-1.24l-.39-2.77l-.18-1.24zm10.11 3.9l3.55 2.19l.85.53v6.5H18.5l-.53-.85l-1.94-3.05l-.53-.85l.1-1l.3-3l.1-1z");
}

</style>
