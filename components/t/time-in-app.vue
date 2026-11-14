<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2xwk667i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:time-in-app" /></template>
<style>
.b2xwk667i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.7 21.5H4v-19h11.5v9.2M8.25 18h3m4.25-3.5h5v1c0 1.25-1.5 2-2.5 2.5c1 .5 2.5 1.25 2.5 2.5v1h-5v-1c0-1.25 1.5-2 2.5-2.5c-1-.5-2.5-1.25-2.5-2.5Z");
}

</style>
