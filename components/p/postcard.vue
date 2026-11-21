<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1atav4tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:postcard" /></template>
<style>
.h1atav4tq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 12H10M6 16H14M2 7C2 5.3431 3.3431 4 5 4H19C20.6569 4 22 5.3431 22 7V17C22 18.6569 20.6569 20 19 20H5C3.3431 20 2 18.6569 2 17V7ZM14 9C14 8.4477 14.4477 8 15 8H17C17.5523 8 18 8.4477 18 9V11C18 11.5523 17.5523 12 17 12H15C14.4477 12 14 11.5523 14 11V9Z");
}

</style>
