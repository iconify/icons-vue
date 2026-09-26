<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3-o5s18u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:quote-single-duotone" /></template>
<style>
.r3-o5s18u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 14.5C8.5 11.0341 10.2982 7.8163 13.25 6C12.5009 6.6386 12.0694 7.5735 12.0694 8.5579C12.0694 9.7588 12.71 10.8685 13.75 11.4689C14.8329 12.0941 15.5 13.2496 15.5 14.5C15.5 16.433 13.933 18 12 18C10.067 18 8.5 16.433 8.5 14.5Z");
}

</style>
