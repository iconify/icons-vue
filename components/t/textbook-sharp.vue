<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="r6xsfz4lg"/><path class="k33le7bgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:textbook-sharp" /></template>
<style>
.k33le7bgw {
  d: path("M8.75 6.25h6.5v4.25h-6.5Z");
}

.r6xsfz4lg {
  d: path("M4.75 18.75v-16h14.5v13.5H4.75v2Zm0 0v2.5h14.5v-4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
