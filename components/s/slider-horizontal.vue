<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt8x2-bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:slider-horizontal" /></template>
<style>
.rt8x2-bbf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 19C20 17.34 18.6569 16 17 16H15C13.3431 16 12 17.34 12 19M20 19C20 20.66 18.6569 22 17 22H15C13.3431 22 12 20.66 12 19M20 19H22M12 19H2M2 4V10C2 11.1 2.8954 12 4 12H20C21.1046 12 22 11.1 22 10V4C22 2.9 21.1046 2 20 2H4C2.8954 2 2 2.9 2 4Z");
}

</style>
