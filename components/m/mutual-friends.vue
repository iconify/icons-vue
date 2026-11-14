<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rq8rxzn4p"/><path class="iqh7t6b7l"/><path class="r5cjekb_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mutual-friends" /></template>
<style>
.iqh7t6b7l {
  d: path("M10.75 8a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0ZM3 20.5C3 17.25 5.75 15 9.5 15s6.5 2.25 6.5 5.5");
}

.r5cjekb_s {
  d: path("M8 20.5c0-3.25 2.75-5.5 6.5-5.5s6.5 2.25 6.5 5.5");
}

.rq8rxzn4p {
  d: path("M5.75 8a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
