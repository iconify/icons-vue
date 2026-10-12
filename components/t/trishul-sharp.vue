<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="brpks1taa"/><path class="l_758gh9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trishul-sharp" /></template>
<style>
.brpks1taa {
  d: path("m12 2.75l1.5 3L12 8l-1.5-2.25ZM12 8v7m0 4v2.25m0-8.75c-4 0-6.5-2-6.5-5.5m6.5 5.5c4 0 6.5-2 6.5-5.5");
}

.l_758gh9v {
  d: path("m5.5 3.25l1.25 2.5L5.5 7.5L4.25 5.75Zm13 0l1.25 2.5L18.5 7.5l-1.25-1.75ZM9.75 15h5l-.3.4l-.9 1.2l-.3.4l.3.4l.9 1.2l.3.4h-5.5l.3-.4l.9-1.2l.3-.4l-.3-.4l-.9-1.2l-.3-.4z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
