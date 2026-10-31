<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajdk8_bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vault" /></template>
<style>
.ajdk8_bsu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 3L18 3C19.6569 3 21 4.3431 21 6L21 18C21 19.6569 19.6569 21 18 21L6 21C4.3431 21 3 19.6569 3 18L3 6C3 4.3431 4.3431 3 6 3ZM8.5 7L15.5 7C16.3284 7 17 7.6716 17 8.5L17 15.5C17 16.3284 16.3284 17 15.5 17L8.5 17C7.6716 17 7 16.3284 7 15.5L7 8.5C7 7.6716 7.6716 7 8.5 7ZM3 10L7 10M3 14L7 14M13 11L13 13");
}

</style>
