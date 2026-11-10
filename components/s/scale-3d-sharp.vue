<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxbqevb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scale-3d-sharp" /></template>
<style>
.dxbqevb7l {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.98L15 7.95V4.91L12 3L9 4.91V7.95L12 9.98ZM12 9.98L12 13.01M16 16.05L19 14.02L22 16.05V19.08L19 21L16 19.09V16.05ZM16 16.05L12 13.01M8 16.05L5 14.02L2 16.05V19.09L5 21L8 19.08V16.05ZM8 16.05L12 13.01");
}

</style>
