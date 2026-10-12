<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mddg3hbvg"/><path class="kt3yesq5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:umbrella-sharp" /></template>
<style>
.kt3yesq5y {
  d: path("M12 11v9.5H8.5v-1.75");
}

.mddg3hbvg {
  d: path("M3.25 12.25a8.75 8.75 0 0 1 17.5 0a3.75 3.75 0 0 0-5.83 0a3.75 3.75 0 0 0-5.84 0a3.75 3.75 0 0 0-5.83 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
