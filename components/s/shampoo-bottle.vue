<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iwfu3jbbx"/><path class="utptugb4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shampoo-bottle" /></template>
<style>
.iwfu3jbbx {
  d: path("M7 7.5h4V9l3 2.5V20a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 4 20v-8.5L7 9Zm2 0v-3H6.5V2.75h7l2 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.utptugb4d {
  d: path("M6.75 13h4.5v5h-4.5Zm10-5.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm.75 5.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
