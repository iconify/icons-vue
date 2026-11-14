<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yl9ek9lna"/><path class="l1varkrrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:satellite-search" /></template>
<style>
.l1varkrrm {
  d: path("M5 8.5q4.25.75 3.5-3.5m-.75 2.75L9 9m6.25 8.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4 1.75L21 21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yl9ek9lna {
  d: path("M7.464 11L11 7.464L14.536 11L11 14.536Zm-4.242 4.95l2.828-2.829l2.829 2.829l-2.829 2.828Zm9.899-9.9l2.829-2.828l2.828 2.828l-2.828 2.829ZM6.5 15.5L8 14m6-6l1.5-1.5");
}

</style>
