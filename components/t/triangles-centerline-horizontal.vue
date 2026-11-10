<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iirggoujh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangles-centerline-horizontal" /></template>
<style>
.iirggoujh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 12H2M11.7394 2.13L8.0416 7.61C7.9242 7.78 8.0693 8 8.3021 8H15.6979C15.9307 8 16.0758 7.78 15.9585 7.61L12.2606 2.13C12.1442 1.96 11.8558 1.96 11.7394 2.13ZM11.7394 21.87L8.0416 16.39C7.9242 16.22 8.0693 16 8.3021 16H15.6979C15.9307 16 16.0758 16.22 15.9585 16.39L12.2606 21.87C12.1442 22.04 11.8558 22.04 11.7394 21.87Z");
}

</style>
