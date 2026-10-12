<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cnbrm7a5x"/><path class="vvlubeblb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:save-sharp" /></template>
<style>
.cnbrm7a5x {
  d: path("M3.75 6.25v-2.5h12.6l.824.012l.576.588l2.3 2.3l.588.576l.012.824v12.2H3.75v-2.5Z");
}

.vvlubeblb {
  d: path("M7.75 20.25v-5.5h8.5v5.5m-8-16.5v4h6.5v-4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
