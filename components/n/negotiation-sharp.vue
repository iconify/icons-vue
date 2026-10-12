<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rgzl0nkiq"/><path class="fdao0jv6u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:negotiation-sharp" /></template>
<style>
.fdao0jv6u {
  d: path("M5.75 6.9h5M9 5.15l1.75 1.75L9 8.65M19.25 11h-2v3.5h-7.5v4h6.5l3 2.5v-2.6h2V11z");
}

.rgzl0nkiq {
  d: path("M4.75 2.75h9V11H7.5l-3 2.5v-2.6l-1.764-.222L2.75 8.9V2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
