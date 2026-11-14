<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjjr3h4qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mustache" /></template>
<style>
.zjjr3h4qx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10.5c1.5-2 4.5-1.75 6 .5c.75 1.1 1.75 1.5 3 1c-1 3-4.5 3.5-6.5 2.25c-1-.65-1.75-1.25-2.5-2c-.75.75-1.5 1.35-2.5 2C7.5 15.5 4 15 3 12c1.25.5 2.25.1 3-1c1.5-2.25 4.5-2.5 6-.5Z");
}

</style>
