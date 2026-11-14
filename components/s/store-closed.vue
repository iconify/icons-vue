<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jksggizrl"/><path class="b-d7zabgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:store-closed" /></template>
<style>
.b-d7zabgk {
  d: path("M3 7.5a4.5 4.5 0 0 0 9 0a4.5 4.5 0 0 0 9 0m-9 0v7m-4.75 0h9.5V20h-9.5Zm2.5 2.75h4.5");
}

.jksggizrl {
  d: path("M3 7.5L4.5 3h15L21 7.5M4.5 10.75V21m15-10.25V21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
