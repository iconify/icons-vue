<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ui3ei481s"/><path class="utxbj9bmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:set-square-sharp" /></template>
<style>
.ui3ei481s {
  d: path("M3.75 4.75v15.5h17l-1.06-1.06L4.81 4.31L3.75 3.25z");
}

.utxbj9bmu {
  d: path("M7.25 12.5v4.25h5l-.53-.53l-3.94-3.94l-.53-.53z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
