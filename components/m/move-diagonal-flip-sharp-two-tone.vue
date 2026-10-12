<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufw_3d8lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:move-diagonal-flip-sharp-two-tone" /></template>
<style>
.ufw_3d8lh {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.1757 4.1757L19.8243 19.8243M20 13L20 20L13 20M4 11L4 4L11 4");
}

</style>
