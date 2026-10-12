<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dq8eg4mja"/><path class="h3lofbc2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oasis-sharp" /></template>
<style>
.dq8eg4mja {
  d: path("M10.5 9.5c-2-2.5-5-3-7.25-1.75M10.5 9.5c-.5-3 1-5.5 4-6.25m-4 6.25c2-1.75 5-1.75 7.75 0m-7.75 0c-3-.25-5.5 1.5-6 4m6-4l1.6 4l-.35 3.5");
}

.h3lofbc2n {
  d: path("M2.75 18.75a9.25 2.5 0 1 0 18.5 0a9.25 2.5 0 1 0-18.5 0Zm5.25 0h8");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
