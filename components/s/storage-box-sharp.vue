<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ouu928b9k"/><path class="vktvftqbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:storage-box-sharp" /></template>
<style>
.ouu928b9k {
  d: path("M2.75 4.25h18.5v3.5H2.75zm1.5 3.5h15.5v13.5H4.25v-2Z");
}

.vktvftqbh {
  d: path("M9 10.75h6v2.5H9z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
