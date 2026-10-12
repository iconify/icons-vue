<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="dcbfcebwo"/><path class="b1l6vhbgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:palette-sharp" /></template>
<style>
.b1l6vhbgz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 12.5h.01M8.5 8h.01m3.99-1.5h.01m3.99 1.75h.01");
}

.dcbfcebwo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75a9.25 9.25 0 0 0 0 18.5h1.75v-2.22l-.45-.63l-.5-.583V15.5h3.7a5.25 5.25 0 0 0 4.75-5.25c0-3.85-4.15-7.5-9.25-7.5Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
