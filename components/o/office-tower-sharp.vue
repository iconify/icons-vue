<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="k2m6tibne"/><path class="swjw4g_yw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:office-tower-sharp" /></template>
<style>
.k2m6tibne {
  d: path("M6 20.5v-14l.72-.22l10.56-3.31l.72-.22v18.5H6zm0-9h12m-6-6.87V14");
}

.swjw4g_yw {
  d: path("M10 17h4v4.25h-4z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
