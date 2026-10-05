<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_0iwmpfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-search" /></template>
<style>
.q_0iwmpfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 4C10.6569 4 12 5.3431 12 7C12 8.6569 10.6569 10 9 10C7.3432 10 6 8.6569 6 7C6 5.3431 7.3432 4 9 4ZM10 21L3 21C2.4477 21 2 20.5523 2 20C2 16.6863 4.6863 14 8 14L10 14M21 17C21 18.6569 19.6569 20 18 20C16.3431 20 15 18.6569 15 17C15 15.3431 16.3431 14 18 14C19.6569 14 21 15.3431 21 17ZM20.5 19.5L22 21");
}

</style>
