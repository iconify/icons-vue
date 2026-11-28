<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ppy1axtav"/><path class="a08du-bef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-braces" /></template>
<style>
.a08du-bef {
  d: path("M10 7C9.4477 7 9 7.448 9 8V10.482C9 10.747 8.8947 11.002 8.7071 11.189L8.0732 11.823C8.0264 11.87 8 11.934 8 12C8 12.066 8.0264 12.13 8.0732 12.177L8.7071 12.811C8.8947 12.998 9 13.253 9 13.518V16C9 16.552 9.4477 17 10 17M14 7C14.5523 7 15 7.448 15 8V10.482C15 10.747 15.1054 11.002 15.2929 11.189L15.9268 11.823C15.9737 11.87 16 11.934 16 12C16 12.066 15.9737 12.13 15.9268 12.177L15.2929 12.811C15.1054 12.998 15 13.253 15 13.518V16C15 16.552 14.5523 17 14 17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ppy1axtav {
  d: path("M6 3H18C19.6569 3 21 4.343 21 6V18C21 19.657 19.6569 21 18 21H6C4.3431 21 3 19.657 3 18V6C3 4.343 4.3431 3 6 3Z");
}

</style>
