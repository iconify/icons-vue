<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw86ucbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stamp" /></template>
<style>
.bw86ucbgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 8.2361L14.8025 11.2568C14.919 11.695 15.3156 12 15.769 12L17 12C19.2091 12 21 13.7909 21 16C21 16.5523 20.5523 17 20 17L4 17C3.4477 17 3 16.5523 3 16C3 13.7909 4.7909 12 7 12L8.231 12C8.6844 12 9.081 11.695 9.1975 11.2568L10 8.2361C9.3637 7.6669 9 6.8537 9 6C9 4.3431 10.3431 3 12 3C13.6569 3 15 4.3431 15 6C15 6.8537 14.6363 7.6669 14 8.2361ZM5 21L19 21");
}

</style>
