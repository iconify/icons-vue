<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="javnxvbkv"/><path class="dt6buif6s"/><path class="jfl86sb5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:whisk-sharp" /></template>
<style>
.dt6buif6s {
  d: path("M8.25 8.5v4.25a3.75 6 0 0 0 7.5 0V8.5");
}

.javnxvbkv {
  d: path("M12 2.75V6M5 6h14v2.5H5zm.75 2.5v4.25a6.25 8.5 0 0 0 12.5 0V8.5");
}

.jfl86sb5a {
  d: path("M10.75 8.5v4.25a1.25 3.5 0 0 0 2.5 0V8.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
