<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vx6ye67lo"/><path class="ap09rll1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-call-sharp-fill" /></template>
<style>
.ap09rll1t {
  d: path("M13.3294 4.074L14.0706 4.2726C16.8313 5.0123 18.9877 7.1687 19.7274 9.9294L19.926 10.6706M12.2942 7.9377L13.0353 8.1363C14.4156 8.5062 15.4938 9.5844 15.8637 10.9647L16.0623 11.7058");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vx6ye67lo {
  fill: currentColor;
  d: path("M1 4L1 2C1 1.4477 1.4477 1 2 1L9 1C9.5523 1 10 1.4477 10 2L10 8C10 8.3148 9.8518 8.6111 9.6 8.8L8.3388 9.7459C9.6049 12.3156 11.6844 14.3951 14.2541 15.6612L15.2 14.4C15.3889 14.1482 15.6852 14 16 14L22 14C22.5523 14 23 14.4477 23 15L23 22C23 22.5523 22.5523 23 22 23L20 23C9.5066 23 1 14.4934 1 4Z");
  stroke: none;
}

</style>
