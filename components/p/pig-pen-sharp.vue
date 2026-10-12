<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hhkmqv_xz"/><path class="yi3p30bqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pig-pen-sharp" /></template>
<style>
.hhkmqv_xz {
  d: path("M6 10.5a6 6 0 0 1 .8-3l-.55-3.75L9 5.3a6 6 0 0 1 6 0l2.75-1.55l-.55 3.75a6 6 0 0 1 .8 3v.5a6 3 0 0 1-12 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yi3p30bqm {
  d: path("M9.5 8.5h5v3h-5zM5 16v5.25M9.5 16v5.25m5-5.25v5.25M19 16v5.25m-15.75-2.5h17.5");
}

</style>
