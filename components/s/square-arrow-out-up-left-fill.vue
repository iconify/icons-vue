<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6t1id8su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-out-up-left-fill" /></template>
<style>
.c6t1id8su {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 7L18 7C19.6569 7 21 8.3431 21 10L21 18C21 19.6569 19.6569 21 18 21L10 21C8.3431 21 7 19.6569 7 18L7 15M11 11L3.5 3.5M11 3L3.5 3C3.2239 3 3 3.2239 3 3.5L3 11");
}

</style>
