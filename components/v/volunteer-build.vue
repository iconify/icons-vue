<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xa0ilybwv"/><path class="f1c6vo5jn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:volunteer-build" /></template>
<style>
.f1c6vo5jn {
  d: path("m17.586 13.922l4.242 4.242l-1.414 1.414l-4.242-4.242Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xa0ilybwv {
  d: path("M12.544 19.5H2.5V10L11 2.75L19.5 10v1.856m-4.75 9.394l3.5-3.5");
}

</style>
