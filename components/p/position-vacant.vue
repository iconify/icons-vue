<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geisd4adn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:position-vacant" /></template>
<style>
.geisd4adn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 2.5h7.5V8h-7.5Zm-6 11.5h7.5v6.5h-7.5ZM12 8v3.25M6 14v-2.75h12V14m-1.75 0h3.5m-5.5 2.25v2m7.5-2v2m-5.5 2.25h3.5");
}

</style>
