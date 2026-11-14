<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="snnjfeb4f"/><path class="gmhfd4_gh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:surfboard-leash" /></template>
<style>
.gmhfd4_gh {
  d: path("M4.75 18C5.5 21 8 21.25 9.5 19.5s3.25 1.75 6.25-1m0 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.snnjfeb4f {
  d: path("M18 3q-3 9.5-11.5 14.5a2.12 2.12 0 0 1-3-3Q8.5 6 18 3ZM7 14l7.5-7.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
